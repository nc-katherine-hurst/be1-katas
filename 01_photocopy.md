# photocopier

The `photocopier` function takes in a blueprint to photocopy, which will be a flat (un-nested) object that has a key of `isCopy` which is `false`, and at least one other property. 

The function returns a copy of that object, with `isCopy` set to `true`.

This function needs to be pure, so in your tests you should check:

- The original blueprint object is unchanged.
- The copy that the function returns isn’t accidentally the same object as the blueprint that was passed in.

For example a blueprint could look like this:

```js
const blueprint = {
    isCopy: false,
    title: "A guide to goat rearing",
    mainText: "Feed them",
    author: "Katherine"
}

const copy = photocopier(blueprint)
/* returns
{
    isCopy: true,
    title: "A guide to goat rearing",
    mainText: "Feed them",
    author: "Katherine"
}
*/
```



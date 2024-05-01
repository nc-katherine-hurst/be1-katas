# stackPhotocopier

Time to upgrade our photocopier, it now takes in a pile (an array) of blueprints and must make copies of them (with the `isCopy` property set to `true`).

As before though, this is a pure function so we must make sure:

- that none of the returned objects are the same as the ones passed in.
- the original blueprints are not altered/mutated.

```js
const blueprints = [
  {
    isCopy: false,
    title: "A guide to goat rearing",
    mainText: "Feed them",
    author: "Katherine",
  },
  {
    isCopy: false,
    title: "A lonely title",
  },
  {
    isCopy: false,
    title: "Hello world",
    subtitle: "A dev story",
  },
];
```

should return:

```js
[
  {
    isCopy: true,
    title: "A guide to goat rearing",
    mainText: "Feed them",
    author: "Katherine",
  },
  {
    isCopy: true,
    title: "A lonely title",
  },
  {
    isCopy: true,
    title: "Hello world",
    subtitle: "A dev story",
  },
];
```

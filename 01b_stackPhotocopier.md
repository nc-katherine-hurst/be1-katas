# stackPhotocopier

Time to upgrade our photocopier, it now takes in a pile of blueprints and must make copies of them (with the `isCopy` property set to `true`).

As before though, this is a pure function so we must make sure

- the original blueprints are not altered/mutated
- that none of the returned objects are the same as the ones passed in

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
    title: "hello world",
    subtitle: "something else",
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
    title: "hello world",
    subtitle: "something else",
  },
];
```

# Make a Yellow pages

THIS MIGHT BE REDUNDANT BECAUSE THEY DID CREATEREF

A yellow pages was an ancient text where you looked up people's names and found their phone numbers. In this function we'll make our own Yellow Pages.

The function `makeYellowPages` takes in an array of people, like this:

```js
const people = [
    {
        firstName: "Katherine"
        lastName: "Hurst"
        phoneNumber: 0800001066
    },
    {
        firstName: "Schmatherine"
        lastName: "Hurst"
        phoneNumber: 0800001067
    }
]
```

and turns it into a yellow pages like so:

```js
makeYellowPages(people); // {"Katherine Hurst": 0800001066, "Schmatherine Schmurst":0800001067 }
```

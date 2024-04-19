
## The Grand Goat Race

Every year there is a grand goat race, and you recieve the data about participating goats in the following format:

"Bleaters: 01:10:10, Katherine: 01:30:10, Professor Dandelion 01:20:10"

It's your job to write a function which takes in this information, and returns an object summarising the outcome in this form:

```js
{
    firstPlace: "Mr Bleaters",
    lastPlace: "Katherine",
    averageTime: "01:20:10"
}
```

Describing the winning goat, the goat in last place and the average time of a goat in the race. You calculate the average by adding all the times together and dividing them by the number of goats in the race.

Use `.objectContaining` to build up functionality one key value pair at a time in your tests.



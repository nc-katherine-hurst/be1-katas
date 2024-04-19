
## The Grand Goat Race

Every year there is a grand goat race, and you recieve the data about participating goats in the following format:

`"Bleaters: 01:00:00, Professor Dandelion 00:30:00"`

Where we have the name of the goat, followed by their race time in hours, minutes and seconds.

It's your job to write a function which takes in this information, and returns an object summarising the outcome of the race in this form:

```js
{
    firstPlace: "Professor Dandelion",
    lastPlace: "Bleaters",
    averageTime: "00:45:00"
}
```

This describes the winning goat, the goat in last place and the average time of a goat in the race, rounded up to the nearest second. 

Use `.objectContaining`, or another suitable Jest matcher, to build up functionality one key value pair at a time in your tests.




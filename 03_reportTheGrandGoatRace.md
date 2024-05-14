# The Grand Goat Race

Every year there is a Grand Goat Race, which runs with a minimum of 2 participating goats. The fastest goat wins but there is a consolation prize for the goat with the longest name. You recieve the data about participating goats in the following format:

`"Bleaters: 00:30:00, Professor Dandelion: 01:00:00, Katherine Jr.: 00:45:00"`

Where we have the name of the goat, followed by their race time in hours, minutes and seconds. 

It's your job to write a function which takes in this information, and returns an object summarising the outcome of the race in this form:

```js
{
    firstPlace: "Bleaters",
    goatWithLongestName: "Professor Dandelion",
    averageTime: "00:45:00"
}
```

This describes the winning goat on a key of `firstPlace`, the goat in last place on a key of `lastPlace`, the average time of all the goats in the race, rounded up to the nearest second on a key of `averageTime`, and the goat with the longest name on a key of `goatWithLongestName`.

In the event of any draw, the goat with name that comes first alphabetically wins.

**Try to build up your tests gradually and flexibly, adding separate tests for each key value pair in the returned object.**






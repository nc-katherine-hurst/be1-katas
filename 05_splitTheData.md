# splitTheData

This function takes in data in the following format about people and their favourite games.

```js
const gamerData = [
  {
    id: 1,
    name: "Katherine",
    faveGames: ["Minecraft", "Factorio"],
  },
  {
    id: 2,
    name: "Tim",
    faveGames: ["Bingo", "Minecraft"],
  },
];
```

The function `splitTheData` returns the data reorganised into a new object with keys of `people`, `games` and `gamesPeopleLike`.

So `splitTheData(gamerData)` returns:

```js
{
    people: [
        {
            id: 1
            name: 'Katherine'
        },
        {
            id: 2
            name: 'Tim'
        }
    ],
    games: {
        1: 'Minecraft',
        2: 'Factorio',
        3: 'Bingo'
    }
    gamesPeopleLike: {
        1:1, // Katherine likes Minecraft
        1:2, // Katherine likes Factorio
        2:3, // Tim likes Bingo
        2:1  // Tim likes Minecraft
    }
}
```

It's important we don't change the original data, this function will need to be pure.

**Build up your tests gradually and flexibly, adding separate tests for each key value pair in the returned object.**

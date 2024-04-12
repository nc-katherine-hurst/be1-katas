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

Change how the data is organised into the following:

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

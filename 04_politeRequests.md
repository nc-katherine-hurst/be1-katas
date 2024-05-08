# politeRequests

This function takes in three arguments
    - A string which is an instruction, with a "%" in place of a person's name. Eg. "Feed the cat %"
    - An array of names, e.g. `["Katherine", "Tim", "Caroline", "Suzanna"]`
    - A boolean which determines whether or not the returned instructions will be polite, (i.e. appended with "please").

It must return an array of instruction strings, with the % replaced with each  of the names in the array in turn.
If the boolean is `true`, each instruction must also have "please" added to the end of each string.

For example:

```js
politeRequests("Go to the bank %", ["Katherine", "Tim"], true)
// returns ["Go to the bank Katherine please", "Go to the bank Tim please"]

politeRequests("Fetch me a drink %", ["Caroline", "Suzanna"], false)
// returns ["Fetch me a drink Caroline", "Fetch me a drink Suzanna"]
```


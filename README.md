# Learnings

1. Assigning primitive data type variables to another variable creates a copy of the original variable.
2. Assigning non-primitive data type variables to another variable creates a reference to the original variable.
3. Create a copy of the array with blank ```players.slice()```, ```[].concat(players)```, ```[...players]``` ( Spread Operator ) & ```Array.from(players)```.
4. Create a copy of a Object with ```Object.assign({}, players, { number: 99})```.
5. These methods are only for one level of cloning.
6. Other methods to do a deep clone "lodash deepClone" or ```JSON.parse(JSON.stringify(person))```.
# What-I-Learned-In-Week-6

### Loops and Iterations
```
for ([initialExpression]; [condition]; [incrementExpression]) {
  statement
}
```

* Setup
* Continuation Check
* Change

```
const teacher = 'Colin';
let i = 0;

while  (i < teacher.length) {
    console.log(teacher [i]);
    i = i + 1;
}
```

### Arrays
An array in JavaScript is a type of global object that is used to store data. Arrays consist of an ordered collection or list containing zero or more datatypes, and use numbered indices starting from 0 to access specific items.
```
let seaCreatures = [
    "octopus",
    "squid",
    "shark",
    "seahorse",
    "starfish",
];
```
There are ton of methods like:
* `.push()` adds an item to the end
* `.pop()` removes the last item
* `.shift()` & `.unshift()` removes/adds to the first item

### Notes
Method Chaining and the order matters.

```
const variableName = document
    .querySelector('#arguments')
    .lastElementChild
    .childElementCount
    .toString()
```

Don't chain two methods on one line.

The loop will go through each vowel in the case below to the parameter given.
```
if ('aeiou'.includes(currentCharacter))
```
# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var and let
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a function is a grouping of JS code that does one process.  The scope should be limited to one thing not many for cleaner code.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S.O.L.I.D. STANDS FOR:
S — Single responsibility principle
O — Open closed principle
L — Liskov substitution principle
I — Interface segregation principle
D — Dependency Inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
position 2   ....    fruit[2] 
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
let numberOfApples = 5
let numberOfPears = 3

===  conditional ===>    nemberOfApples > numberOfPears = true 

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model   
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
The latest ECMAScript standard defines nine types: Six Data Types that are primitives, checked by typeof operator: undefined : typeof instance === "undefined" Boolean : typeof instance === "boolean" ... BigInt : typeof instance === "bigint"

primitives: string, number, Boolean, BigInt, undefined, null 

```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
parameter is from the point of the function what it is looking for... And argument is what gets passed into the function at the time of calling it.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are data that are stored on the stack. ... Reference values are objects that are stored in the heap. Reference value stored in the variable location is a pointer to a location in memory where the object is stored. Primitive types include Undefined , Null , Boolean , Number , or String .
```
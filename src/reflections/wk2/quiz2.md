# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
```
var, let, const
```
**2.** What is the definition of a function?
<!-- enter your answer in the space below -->
```
A function is a block of code in javascript that tells the program what to do in specific situations.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S Single Responsibility

O: Open/Close

L: Liskov Substitution

I: Interface Segregation

D: Dependency Inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
```
Index = 2. It is the third item, but the first in an array has an index of 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
```
if (x > 10) {
  return x
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
```
A Statement
```
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. First accessed by the HTML file.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Undefined, Boolean, Number, String, BigLnt, Symbol, Object, Function, and Null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are created and defined within the function, whereas arguments are values that are already defined and ready to be invoked.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are global and reference values are local
```
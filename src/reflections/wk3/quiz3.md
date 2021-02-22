# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, Polymorphism, Inheritance, Abstraction
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Bundling like data
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility Principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
Class variables have a larger scope.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Proxy objects serve as a substitute for the actual object that the client can change, but not reassign.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
It allows for 'separation of concerns.' That means each controller/service handles one thing, rather than having a js file that handles different types of things.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller takes in data from the html/main.js and passes it on to the service.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Service does all the brunt work of the js. Takes  in the data from the controller and is able to manipulate the data in the Proxy.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model is the base structure of your data. It allows you to control what kind of data the user can send in.
```


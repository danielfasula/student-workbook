# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is a declarative region that provides a scope to the identifiers (the names of types, functions, variables, etc) inside it.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A class combines the fields and methods into a single unit. A construct is a collection of different data types under a single unit.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
public void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
`String` is in indicator of what data type will be returned from the method.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract prevents inheritence of a class or certain class members that were previously marked virtual.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual keyword is used to modify a method, property, indexer, or event declared in the base class and allow it to be overridden in the derived class. 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, Protected, Internal, Private
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Private Methods can only be used inside the class they are instantiated in.
```
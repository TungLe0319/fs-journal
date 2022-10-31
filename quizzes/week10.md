# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The namespace keyword is used to declare a scope that contains a set of related objects. You can use a namespace to organize code elements and to create globally unique types.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
structure by default have all its member as “public”, and class by default have all its member “private”.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
VOID method
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
the datatype you expect to use/return , in the example its "Vroooom"
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
preventing the class car to not be an actual full class but rather a base class that will be inherited
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual keyword is used to modify a method, property, indexer, or event declaration and allow for it to be overridden in a derived class. For example, this method can be overridden by any class that inherits it:
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public 
abstract
internal
private
virtual
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the methods within the file or class
```
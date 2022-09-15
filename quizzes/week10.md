# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespace is a scope where you can access values declared in the scope.

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Struct cannot have a constructor and class can, struct is like a mini version of class.

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Private static class

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
the data type

```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
abstract is preventing the class from showing internal details

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
virtual is used to modify a method.

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal, protected

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the server can access a private class.

```
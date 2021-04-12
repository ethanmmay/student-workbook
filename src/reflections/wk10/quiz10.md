# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
  A namespace is the reference tag for a class or C# class file that is unique and used to access methods and classes within the namespace.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
  A class has more permanence.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
  void
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
  return type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
  instantiation
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
  redefinable class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
  public, private, internal and private protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
  other code in it's class/struct
```
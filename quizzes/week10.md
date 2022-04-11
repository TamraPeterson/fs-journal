# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
        A namespace declares the scope of the class.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
        A struct is a lighter version of a class.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
        The void method doesn't have a return type.
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
        The string is what is returned
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
        Virtual makes the method interchangeable
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
        public, private, protected, internal 
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
        You can access by instantiating an instance of the class.
```
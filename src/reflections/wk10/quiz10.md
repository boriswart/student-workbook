# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
it is a class division of code so to keep concerns separated.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
class contains data and methods while struct contains only data .
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
new
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
virtual gets created automaticly
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
string gets returned by start
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
 abstract classes are either partially implemented or not implemented at all.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
virtual modifies start
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
virtual abstract 
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only can be accsessed from within class.
```
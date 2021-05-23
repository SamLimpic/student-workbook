# C# Fundamentals

**1.** What is the purpose of a `namespace`?

<!-- enter you answer in the space below -->

```
It distinguishes the specific file you are working in, and communicates that to other parts of the application
```

**2.** What is the difference between a `class` and a `struct`?

<!-- enter you answer in the space below -->

```
Structs cannot have default constructors, are standalone value types, and can be instantiated without the use of an Operator
```

**3.** What is the method that returns an instance of a class, yet it has no return type?

<!-- enter you answer in the space below -->

```
A "void" method
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
"public"
```

**6.** In the example what is `string` an indication of?

<!-- enter you answer in the space below -->

```
The type of value being returned
```

**7.** In the example what is `abstract` preventing?

<!-- enter you answer in the space below -->

```
It prevents the class "Car" from being modified, as its being used exclusively as a reference value
```

**8.** In the example what is the purpose of `virtual`?

<!-- enter you answer in the space below -->

```
Virtuals are temporary data collections, not saved in memory
```

**9.** Name four access modifiers:

<!-- enter you answer in the space below -->

```
Public, Private, Protected, and Internal
```

**10.** If you set a class or method to private, what can access it?

<!-- enter you answer in the space below -->

```
Only the developer, not the User
```

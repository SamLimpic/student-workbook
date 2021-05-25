# Day 1 - INHERITANCE AND INTERFACES

## Daily Journal

I think I'm starting to get a feel for C#... Bringing interfaces into the mix really highlighted how useful C# can be to effectively architect your backend, and how easy it really is to take a basic framework and apply it to many different variables with little deviation.

We'll see how the many-to-many relationships shake out, but if we stick on this track then I'll probably swap over to C# for the majority of my backend work.

Though it'll definitely be through Mongo... %$@& SQL.

## Daily Challenges

Morning:

Afternoon: https://github.com/SamLimpic/cs-burger-shack

### Read "Foundations of C# > C# Inheritance"

1. What does Inheritance accomplish for us in C#?
   It allows you to describe the relationship between a Parent and Child class, and what attributes the Child inherits from the Parent

2. How does Member inheritance work in C#? Does a class inherit all members of the base class?
   All members of a class are inherited, save for the Constructor and Finalizer, though not all of them may be visible.

3. How does accessibility affect inheritance?
   A property's accessibility does not affect its inheritance, but rather its visibility.
   Public properties are visible, while Private, Protected, and Internal properties are not.

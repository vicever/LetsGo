# Notes

* Formatting floats support decimal places to show: `%.2f`
* You don't have `class` but `struct`. Structs are mutable.
* You don't have type hierarchies either.
* There isn't a `new` operator for structs. You have to create your own `New` function
* Go Methods are much like extension methods in C# `func (type T) Name(params) return_type {}` vs `public static return_type Name(this type, params) {}`
* Interfaces are just like C# interfaces. But, you don't to explicitly declare that your type implement them
* Formatting `%#v` shows a `ToString` with property names

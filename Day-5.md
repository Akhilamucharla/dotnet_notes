## C# Language Features

- Generics -> introduced in .Net 2.0
- Delegates -> introduced in .Net 3.5
- Named / optional -> 3.0

> Implicit typed local variable -> 3.0

- var -> should be used when we are not sure about data type to be used
  ![alt text](image-81.png)
  - Rules:
    - this feature is applicable only as `Local variable`
    - can't be used as method parameter
    - multiple variable not supported (ex: var m,n,o;)
    - you have to assign the value while declaring
      - ![alt text](image-82.png)
    - cannot assign Null values
      - ![alt text](image-83.png)

> Nullable Types

- ![alt text](image-84.png)
- using nullable types we can assign null values for int, float datatypes
- we achieve nullable types by using `?`
  - ![alt text](image-85.png)

> Types

- 2 types:
  - Reference types : class, string , interference , object , delegate
  - value type : int, float, double, boolean, byte

> Extension Methods

- ![alt text](image-86.png)
- we can add new methods to .Net built in type
- RULES:
  - method and class should be static
  - the methods has to take 1 parameter
- ![alt text](image-87.png)
- ![alt text](image-88.png)

> InLine Warning

- using inline warning feature we can disable the warning messages
- use `#pragma warning disable` -> disables
- use `#pragma warning restore` -> enables
  ![alt text](image-89.png)
- `#region` & `#endregion`usage
  ![alt text](image-90.png)

> object and collection initializer

![alt text](image-91.png)

> Automatic Properties

![alt text](image-92.png)

> Partial Methods (feature available only in .Net core)

- partial methods can be used only inside partial classes
- partial methods = declaration + implementation
- declaration and implementation happens in 2 different files
- ![alt text](image-93.png)

> Anonymous Type

![alt text](image-94.png)

> Lambda Expressions

- for single line methods we can use this
- ![alt text](image-95.png)

> Dynamic support/keyword -> introduced in .net 4.5

- it is same like var , but the problems in var are removed in dynamic
- ![alt text](image-96.png)
- datatype can be changed for the same variable in dynamic
- ![alt text](image-97.png)
- ![alt text](image-98.png)
- problems are resolved only at run time (i.e, the errors are not encountered during compile time,errors are shown only after execution starts)

> Office programability

- ![alt text](image-99.png)

> Covariance and Contravariance (different)

- ![alt text](image-101.png)
- ![alt text](image-100.png)

## LINQ (Language Integrated Query)

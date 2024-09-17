> Access specifiers

- pubic
- private (default)
- protected (only incase of inheritance)
- internal
- protected internal

![alt text](image-16.png)

> Method with parameters

![alt text](image-17.png)

> Methods with optional parameters

![alt text](image-19.png)

> named parameter

![alt text](image-18.png)

> Out keyword

- when we want to return multiple values from a method , we use out keyword

![alt text](image-20.png)

## Arrays

- Collection of variables
  ![alt text](image-21.png)

- 3 types:
  - single dimension -> an array which can hold only one row at a time
    ![alt text](image-23.png)
  - multi dimension -> an array which can hold morethan one row at a time
    ![alt text](image-29.png)
    ![alt text](image-30.png)
    ![alt text](image-31.png)
    - Dynamically take input from user
      ![alt text](image-34.png)
  - jagged array -> it is a type of multi dimension array , but in this case , row is fixed and columns not fixed
    ![alt text](image-32.png)
    ![alt text](image-33.png)

> Loops

![alt text](image-24.png)
![alt text](image-25.png)

> Array methods

![alt text](image-26.png)

> To get values dynamically

![alt text](image-27.png)

- it allocates 3 memory spaces

# Object Oriented Programming

in real life,

- properties -> Data members -> Attributes
- Behaviour -> Functions -> Method

![alt text](image-35.png)
![alt text](image-36.png)
![alt text](image-37.png)
![alt text](image-38.png)

> instead of varaiables , use validations by creating Properties

![alt text](image-39.png)
![alt text](image-40.png)

- `Propfull` command can be used to get the basic code of property in Visual studio
- `prop` command is used if there are not validations . it is called `automatic property`

![alt text](image-41.png)
![alt text](image-42.png)
![alt text](image-43.png)

> Object initializer

![alt text](image-44.png)

> Types of Classes

1. instance class (default): any class which supports object creation is known as instance class (instance means object)

2. static class : it only contains static members only (non static not allowed)(in this case we cannot create objects,we can call members by using class names)
   ![alt text](image-46.png)

3. sealed class : this type of class cannot be inherited(object creation possible)
   ![alt text](image-47.png)

4. abstract class : cannot create object for abstract class but inheritence is allowed
   ![alt text](image-48.png)

5. partial class : this will allow to share the class members in more than 1 file.

> Constructors

- function having the same name as class name
  ![alt text](image-49.png)
  ![alt text](image-50.png)

- 2 types of constructors:
  - instance constructor (called everytime when ever an object is called )
  - static constructor (called only once in a lifetime)

> Property Accessor Visibility

![alt text](image-51.png)

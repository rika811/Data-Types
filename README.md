# Data types
![Screenshot 2023-04-08 at 10 39 13 PM](https://user-images.githubusercontent.com/91966167/230734090-33042c0e-3b8b-4baa-b2e4-fd85fe5cdb89.png)
Basic Data Types
In C language, basic data types are used to store values in integer and decimal forms. It supports both signed and unsigned literals. There are four basic data types, in both signed and unsigned forms:

Int
Float
Double
Char
The memory size of these data types can change depending on the operating system (32-bit or 64-bit). Here is the table showing the data types commonly used in C programming with their storage size and value range, according to the 32-bit architecture.

Derived Data Types
The primitive or basic data types are used to store single values of different forms, but what if you need to store more values of the same data type? Here, derived data types allow you to combine the basic data types and store multiple values in a single variable.

Derived data types are defined by the user itself, which means that you can aggregate as many elements of similar data types as required. There are four types of derived data types:

Array
Pointer
Structure
Union

Have a look at the output of the program:

Student name = George
Roll No = 5
Average Marks = 82.500000
Roll Number = 1118109696
In the above example, the union student has three variables, name, roll no, and marks. The variable name can have a maximum of 25 characters, which means that the size would be 25 bytes. Similarly, roll no will have 4 bytes, and the average marks will also have 4 bytes.

Since the variable with maximum storage size here is ‘name’, the size of the union student will be 25 bytes. If the variable ‘name’ has some value in it and you assign a value to the roll no, the value in the ‘name’ will be replaced by the ‘roll no’ in the memory.

Enumeration Data Type
Enumeration is a user-defined data type used to assign names to the integral constants and enhance the readability of your program. The keyword used for enumeration is ‘enum’ with a syntax similar to structure:



There are two main reasons why enumerations are better than ‘#define’:

Enum constants get default values by the compiler
They can be declared in the local scope

Void Data Type
Void is a data type in C language that does not refer to any value of any type. It is mostly used as the return type in functions. You can declare the void pointers to take the address of variables from any data type. These pointers are often called ‘generic pointers.’


OUTPUTS-

Structure-![Screenshot 2023-04-08 at 10 15 59 PM](https://user-images.githubusercontent.com/91966167/230733180-b23c641a-0d54-4906-9326-64c1dff68842.png)

Union- ![Screenshot 2023-04-08 at 10 18 55 PM](https://user-images.githubusercontent.com/91966167/230733234-db92df4c-a923-486c-8d92-4a4355faae1c.png)

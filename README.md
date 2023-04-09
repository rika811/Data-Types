# Structures and Unions

What is a Structure in C?

A Structure is a type of data that is user-defined. It is available in the C programming language that allows a user to combine together logically related data items of various data types. Structures basically represent a record. All of its elements get stored in the contiguous memory locations. A Structure type- the Variables- can store more than one data item from raging data types all under one name.

Syntax of Declaring a Structure

struct [structure name]

{

type member_1;

type member_2;

. . .

type member_n;

};

What Is a Union?

A Union is a type of data that is user-defined. It is just like the structure. The Union combines various objects of different sorts and sizes together. A user can define a Union using many members, but only one of them holds a value at any given time. It provides you with an efficient way of using a single memory location for various purposes. Thus, varying objects can share a similar location.

Syntax of Declaring a Union

union [union name]

{

type member_1;

type member_2;

. . .

type member_n;

};




OUTPUTS-

Structure-![Screenshot 2023-04-08 at 10 15 59 PM](https://user-images.githubusercontent.com/91966167/230733180-b23c641a-0d54-4906-9326-64c1dff68842.png)

Union- ![Screenshot 2023-04-08 at 10 18 55 PM](https://user-images.githubusercontent.com/91966167/230733234-db92df4c-a923-486c-8d92-4a4355faae1c.png)

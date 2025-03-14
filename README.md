# C_Fundimentals
My understanding in C, More like a checklist of thisngs to know in C

1) Data type
*************
- char, 
- int
- float
- void
- double
=============================================
2) Control flow | Comparison:
******************************
if, else if, else(default go to)
==============================================
3) Function ++++++
*******************

<return_type> function(type param1, type param...)
{
	- do something
	return ();
=============================================
4) Struct <---- is a user-defined datatype +++++
********************************************

Example: struct contain student data - student's name, age, subjects[array] - English, Math, History.

typedef char str;

typedef struct s_data
{
	Student's name		str;
	age 				int;
	Subjects			array;

	void function_1(char *)
} t_data;
===============================================
5) Pointers with function:
***************************

string[i++]

*string++

*string - 5

#Example of string[i++]:
-------------------------
	^
	|
#include <stdio.h>
int main() {
    char string[] = "Hello";
    int i = 0;

    printf("%c\n", string[i++]); // H (i becomes 1 after this)
    printf("%c\n", string[i++]); // e (i becomes 2 after this)

    return 0;
}

#Example of *string++:
-----------------------
	^
	|
#include <stdio.h>
int main() {
    char string[] = "Hello";
    char *ptr = string;  // Pointer to first character

    printf("%c\n", *ptr++); // H (ptr moves to next character)
    printf("%c\n", *ptr++); // e (ptr moves again)

    return 0;
}
__________________________________________
function (char *ptr, int *num)

int main{
	char *name = "Jason";
	int num = 10;
	function(name, &num);                 
}

========================================================
6) Constants & keywords:
************************
========================================================			
7)Input & Output(printf & scanf):
*********************************
>Format specifiers:
>Escape sequences:
========================================================
8) Operators & Expressions:
***************************
Relational and logical Opreators:
---------------------------------
Arithmetic Operators:
---------------------
Bitwise Operations:
-------------------
Assignment Operators:
---------------------
Increment & Decrement Operators:
--------------------------------
	



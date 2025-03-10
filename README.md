# C_Fundimentals
My understanding in C, More like a checklist of thisngs to know in C

1) Data type
*************

- char, 
- int
- float
- void
- double

default - signed (-ve && + ve)
- unsigned (0 - +ve) 

Example:
char *str
unsigned char *str

==========================================================================

2) Control flow | Comparison:
******************************

if, else if, else(default go to)


Exmample:
if (TRUE && (TRUE || FALSE))
	- do A
else
	- do B

=============================================================================
	
3) Function ++++++
*******************

<return_type> function(type param1, type param...)
{
	- do something
	return ();
}


bool ft_isdigit(char c)
{
	return(c >= '0 && c <= '9');
}

int main()
{
	if (ft_isdigit('Q'))
}


=============================================================================

4) Struct <---- is a user-defined datatype +++++
*************************************************


Example: struct contain student data - student's name, age, subjects[array] - English, Math, History.

typedef char str;

typedef struct s_data
{
	Student's name		str;
	age 				int;
	Subjects			array;

	void function_1(char *)
} t_data;

int main()
{
	t_data myData;
	myData.name = "Jason"
}

===========================================================================

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

	i) char *ptr ->A pointer to a character (used for handling strings).

	ii)int *ptr ->A pointer to an integer (used for modifying the value of num inside the function).

	iii)char *name->"Jason" is a "string literal", and in C, string literals are stored in read-only memory.
			 Internally in the memory adress, this is how "Jason" is stored in memory:
			{	
				J   a   s   o   n   \0  (null terminator)
				^ (points to 'J')
			}
===================================================================================
6) Constants & keywords:
************************
	
	i)const ->
	ii)#define ->


====================================================================================				
7)Input & Output(printf & scanf):
*********************************

>Format specifiers:
	- [%s] ->
	- [%d] ->
	- [%f] ->
	- [%c] ->

>Escape sequences:
	- [\n] ->New line.
	- [\t] ->
	- [\\] ->


=====================================================================================
8) Operators & Expressions:
***************************

Relational and logical Opreators:
---------------------------------
	-[==] -> Equal to.
	-[||] -> Or.
	-[>] ->More than.
	-[<] ->Less than.
	-[<=] ->Less than equal to.
	-[>=] ->more than equal to.
	-[&&] -> and.
 	-[!=] ->Not equal to.
	-[!] ->Not/ No.

Arithmetic Operators:
---------------------
	-[+] ->Plus operator.
	-[-] ->Minus operator.
	-[*] ->Multiplication operator.
	-[/] ->Division operator.
	-[%] ->

Bitwise Operations:
-------------------
	-[&] ->
	-[|] ->
	-[^] ->
	-[~] ->
	-[>>] ->
	-[<<] ->

Assignment Operators:
---------------------
	-[=] ->
	-[+=] ->
	-[-=] ->
	-[*=] ->
	-[/=] ->
	-[%=] ->

Increment & Decrement Operators:
--------------------------------
	-[++] -> Increment.
	-[--] -> Decrement.

=========================================================================
9)


# C-Programming

What is C Language?
C programming language, the pioneer of programming languages, is a procedural programming language. Dennis Ritchie created it as a system programming language for writing operating systems. It is one of the most popular programming languages because of its structure, high-level abstraction, machine-independent feature, etc. and is a great starting point for anyone wanting to get into coding. 

C is also used a lot in low-level system programming, embedded systems, and hardware. It has also been heavily optimized over the years and is still used to write sophisticated software such as the FreeBSD operating system and the XNU kernel. Low-level memory access, a small collection of keywords, and a clean style are all qualities that make the C language excellent for system programmings, such as operating system or compiler development. 

C is a low-level programming language that can be directly interfaced with the processor. It offers minimal abstraction and maximal control, making it an attractive option for developers who want to write efficient code. 

C Basic Interview Questions
1. Why is C called a mid-level programming language?
C has characteristics of both assembly-level i.e. low-level and higher-level languages. So as a result, C is commonly called a middle-level language. Using C, a user can write an operating system as well as create a menu-driven consumer billing system.

2. What are the features of the C language?
Some features of the C language are- 

It is Simple And Efficient. 
C language is portable or Machine Independent.
C is a mid-level Programming Language. 
It is a structured Programming Language.
It has a function-rich library. 
Dynamic Memory Management.
C is super fast.
We can use pointers in C.
It is extensible.
3. What is a token?
The individual elements of a program are called Tokens. There are following 6 types of tokens are available in C:

Identifiers
Keywords
Constants
Operators
Special Characters
Strings

4. What is the use of printf() and scanf() functions? Also explain format specifiers?
printf() is used to print the output on the display.
scanf() is used to read formatted data from the keyboard. 
Some datatype format specifiers for both printing and scanning purposes are as follows:

%d: It's a datatype format specifier for printing and scanning an integer value. 
%s: It's a datatype format specifier for printing and scanning a string. 
%c: It's a datatype format specifier for displaying and scanning a character value.
%f: The datatype format specifier %f is used to display and scan a float value.
5. What's the value of the expression 5["abxdef"]?
The answer is 'f'.

Explanation: The string mentioned "abxdef" is an array, and the  expression is equal to "abxdef"[5]. Why is the inside-out expression equivalent?  Because a[b] is equivalent to *(a + b) which is equivalent to *(b + a) which is equivalent to b[a].

6. What is a built-in function in C?
The most commonly used built-in functions in C are sacnf(), printf(), strcpy, strlwr, strcmp, strlen, strcat, and many more.

Built-function is also known as library functions that are provided by the system to make the life of a developer easy by assisting them to do certain commonly used predefined tasks. For example, if you need to print output or your program into the terminal, we use printf() in C.

7. What is a Preprocessor?
A preprocessor is a software program that processes a source file before sending it to be compiled. Inclusion of header files, macro expansions, conditional compilation, and line control are all possible with the preprocessor.

![image](https://user-images.githubusercontent.com/59536110/181610090-842dd6d9-430b-425a-a4c9-2097c6f98d7e.png)

8.
In C, What is the #line used for?
In C, #line is used as a preprocessor to re-set the line number in the code, which takes a parameter as line number. Here is an example for the same.
![image](https://user-images.githubusercontent.com/59536110/181610198-fd82b234-9a64-40a0-bdff-d7c35f1e36b4.png)

Return Value:

On successful conversion, it returns the desired integer value
If the string starts with alpha-numeric char or only contains alpha-num char, 0 is returned.
In case string starts with numeric character but is followed by alpha-num char, the string is converted to integer till the first occurrence of alphanumeric char.
![image](https://user-images.githubusercontent.com/59536110/181610254-c6b45b3c-4550-41b8-96f4-f9a747e58afa.png)

10. How can a number be converted to a string?
The function takes a pointer to an array of char elements that need to be converted, and a format string needs to be written in a buffer as a string

int sprintf(char *str, const char *format, ...)

This section contains general questions and answers about shell scripting

Q. What is Shell?
Shell is a program which is used to execute unix command. or we can shay shell is an interface between kernel and user.

https://www.tutorialspoint.com/unix/unix-getting-started.htm

Q. What is Unix?
It's a multi user OS. The core of unix is Kernel, which interact with Hardware and perform various tasks like Memory management, task scheduling and file management.

Q. Variants of Shell?
C Shell, Bourse Shell, Korn shell are the most famous once.

Q. Unix permission system
Permission system is containd of 10 digits.
drwxrwxr-x
0123456789

- [0] - Always represents the type e.g. file, diireectory, alias etc.
- [1,2,3] - User permission (u)
- [4,5,6] - Group permisssion (g)
- [7,8,9] - Other world permission (o)

Each group represents 3 operations i.e.

- Read (r)
- Write (w)
- Execute (x)

Q. Unix meta characters
'_' '?' are two meta characters. _ is used to match 0 or more characters and ? is used to match single character.

# C/C++/SDL Workshop
Workshop #3: Basics of C/C++ with an introduction to SDL (Making a game from scratch)

### Objectives
- Introduce the fundamentals of the C/C++
  - Environment setup
  - Variables, Pointers, Control Statements, Functions, Importing Libraries
- Application and use of Simple Directmedia Layer (SDL)
  - Create a window & load sprites
  - Keyboard input
  - Move sprites

### Prerequisites
- Basic understanding of programming logic (Maybe you've experimented with Python, Java, or some other programming language)
- Visual Studio Community 2010/2015/2017 Pre-installed ([Download Here](https://www.visualstudio.com/thank-you-downloading-visual-studio/?sku=Community&rel=15))
- Clone of this repository

## The Basics of C/C++
### Variables
Variables are created and stored like so:
```c
int myInt = 5;
```
``` int ``` stands for the variable type and ``` myInt ``` is the name of the variable. ``` = ``` is the assignment operator, used to assign values to variables. In this case, we are setting myInt to 5. Every statement in c/c++ ends in a semicolon ``` ; ```.

After you create a variable for the first time, you don't have to include the typename again, like this:

```c
myInt = 3;
```

##### Some primative (most basic basic) variable types:
- **int** Whole numbers *...-1, 0, 1, 2...*
- **float** Decimal numbers *14.3325*
- **char** Single Characters *'A', 'B', 'C', 'D'*

##### Doing math

### Pointers
Pointers are both a complex and powerful feature of C/C++. For this workshop, just know that a pointer points to a variable. It's like a bookmark for a website. You can use the bookmark across all your devices, and it will still go the same website. We will use pointers for window creation and rendering sprites later on.

### Control Statements
Control statments are used to control the flow of code by testing conditions. The most basic type of control statement is the if/else. The if or if/else statement is used to test a condition for being true or false, then executing code for the right situation.
```c
float pi = 3.14;
if (pi = 3.14) {
  printf("We have PI!");
}
```
In this case, our code would print "We have PI!"

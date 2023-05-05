# GAYATRI VIDYA PARISHID COLLEGE OF ENGINEERING (AUTONOMOUS)

## PPSUC MID-1 ANSWERS 2021-22



### 1(a) Explain different types of problem-solving strategies (5M)

**Ans:** There are several problem-solving strategies that can be used to solve different types of problems. Here are a few examples:


1. Trial and error: This strategy involves trying different solutions until you find one that works. It can be helpful for solving problems that have multiple possible solutions or for problems where the best solution is not immediately obvious.


2. Algorithmic: This strategy involves using a step-by-step approach to solving a problem. It is often used in mathematical and computer science problems and involves breaking the problem down into smaller, more manageable steps.


3. Heuristic: This strategy involves using rules of thumb or educated guesses to solve problems. It can be useful for solving problems where there is no clear solution or for problems where the best solution is not immediately apparent.


4. Lateral thinking: This strategy involves looking at a problem from a different perspective and using creative thinking to find a solution. It can be useful for solving problems that require a unique or innovative solution.


5. Divide and conquer: This strategy involves breaking a problem down into smaller, more manageable parts and solving each part separately. It can be helpful for solving complex problems or problems that involve multiple components.


6. Root cause analysis: This strategy involves identifying the underlying cause of a problem and addressing it directly. It can be useful for solving problems that have recurring or persistent issues.


These are just a few examples of problem-solving strategies. The best strategy to use will depend on the specific problem you are trying to solve and the resources you have available.


### 1(b)  Define a flowchart? Draw a flowchart to find a given integer is even or odd (5M)

**Ans:** A flowchart is a graphical representation of a process or algorithm. It uses different shapes and arrows to show the flow of steps and decisions in a process.


Here's a simple flowchart that checks whether a given integer is even or odd:


```
+--------------+        +--------------+
|   Start      |        |  Number is   |
|              |        |   Even       |
+--------------+        +--------------+
        |                         |
        | Yes                     | No
        |                         |
+--------------+        +--------------+
|    Input     |        |  Number is   |
|   Number     |------->|    Odd       |
+--------------+        +--------------+
        |                         |
        | Done                    | Done
        |                         |
+--------------+        +--------------+
|    Stop      |        |    Stop      |
+--------------+        +--------------+
```


In this flowchart, the process starts with the "Start" symbol and then prompts the user to input a number. The flow then continues to the diamond-shaped decision symbol where it checks whether the number is even or odd. If the number is even, the flow proceeds to the "Number is Even" symbol and stops. If the number is odd, the flow proceeds to the "Number is Odd" symbol and stops. Finally, the process ends with the "Stop" symbol.


Note that there are many ways to design a flowchart to solve a particular problem, and the specific shapes used and the layout of the flowchart may vary depending on the problem being solved and the preferences of the person creating the flowchart.




### 2(a) What is an algorithm? Write algorithm for swapping of two numbers and analyze with example (5M)

**Ans:** An algorithm is a set of well-defined instructions for solving a problem or accomplishing a task. Here's an algorithm for swapping two numbers:


```c
Step 1: Input the two numbers A and B
Step 2: Set a temporary variable temp to store the value of A
Step 3: Assign the value of B to A
Step 4: Assign the value of temp to B
Step 5: Output the swapped values of A and B
```


Let's analyze this algorithm with an example. Suppose we want to swap the values of A = 5 and B = 9.


- Step 1: We input A = 5 and B = 9
- Step 2: We set temp = A, which means temp = 5
- Step 3: We assign the value of B to A, which means A = 9
- Step 4: We assign the value of temp to B, which means B = 5
- Step 5: We output the swapped values of A and B, which are A = 9 and B = 5


In the end, the algorithm swaps the values of A and B by temporarily storing the value of A in a variable called temp, then assigning the value of B to A, and finally assigning the value of temp to B. This algorithm can be used to swap the values of any two variables.




### 2(b) Explain the steps involved in problem solving (5M) 
**Ans:** Problem-solving in C involves applying the general problem-solving process to programming tasks. Here are the steps involved:

1. Define the problem: The first step in problem-solving in C is to clearly define the problem. This involves understanding what the problem is, what input is required, and what the desired output is.

2. Plan the solution: Once the problem has been defined, the next step is to plan a solution. This involves breaking the problem down into smaller, more manageable parts and determining what functions and data structures will be required to solve it.

3. Write the code: After planning a solution, it's time to write the code. This involves coding each function and data structure that was identified in the planning phase.

4. Compile the code: Once the code has been written, it must be compiled to ensure that there are no syntax errors. This involves using a compiler to translate the code into machine language that the computer can understand.

5. Test the code: After compiling the code, it's time to test it. This involves running the program with various inputs to ensure that it produces the desired output and that there are no logical errors.

6. Debug the code: If any errors are found during testing, it's time to debug the code. This involves identifying the source of the error and making the necessary changes to the code.

7. Document the code: Once the code is working correctly, it's important to document it. This involves adding comments to the code to explain how it works, what it does, and any limitations or assumptions that were made during the development process.

By following these steps, C programmers can work through programming tasks and come up with effective solutions that address the underlying problem.



### 3(a)  Explain the Structure of C program with an example program. (5M)
**Ans:** The structure of a C program consists of several parts, including:


1. Preprocessor Directives: These are special commands that begin with a # symbol and are used to provide instructions to the C preprocessor. Preprocessor directives are typically used to include header files, define macros, or conditionally compile code. 


2. Function Prototypes: A function prototype is a declaration of a function that specifies the function's return type, name, and parameter list. Function prototypes are typically placed at the beginning of a program to provide a clear understanding of the functions being used.


3. Global Variables: Global variables are variables that are declared outside of any function and can be accessed by any part of the program. Global variables are typically used to store data that needs to be shared across multiple functions.


4. Main Function: The main function is the entry point of a C program and is where the program starts executing. The main function typically contains declarations of local variables, function calls, and the program's main logic.


Here is an example C program that demonstrates this structure:


```c
#include <stdio.h>


// Function prototype
void greetUser(char name[]);


// Global variable
int age = 30;


int main() {
   // Local variables
   char name[20];


   printf("Enter your name: ");
   scanf("%s", name);


   greetUser(name);


   printf("You are %d years old\n", age);


   return 0;
}


// Function definition
void greetUser(char name[]) {
   printf("Hello, %s!\n", name);
}
```


In this example program, we first include the standard input/output header file using a preprocessor directive. We then declare a function prototype for a function called `greetUser`, which takes a character array as an argument. 


Next, we declare a global variable called `age`, which is initialized to 30. 


In the `main` function, we declare a local variable called `name`, which is an array of characters with a length of 20. We then prompt the user to enter their name using `printf` and `scanf`, respectively. 


We then call the `greetUser` function with the user's name as an argument. 


Finally, we print the user's age using the global variable `age` and return 0 to indicate that the program has executed successfully.


Overall, this example demonstrates the basic structure of a C program, including the use of preprocessor directives, function prototypes, global variables, and the main function.




### 3(b)  Illustrate the differences between while and do-while with example (5M)
**Ans:** In C language, both while and do-while loops are used for repetitive execution of code. However, there are some differences between the two. 

The while loop checks the condition before executing the code block, while the do-while loop checks the condition after executing the code block. Here's an example to illustrate the differences between the two:

```c
#include <stdio.h>

int main() {
   int x = 5;
   
   // while loop
   printf("While loop:\n");
   while(x > 10) {
      printf("x is greater than 10\n");
      x++;
   }
   
   // do-while loop
   printf("Do-while loop:\n");
   do {
      printf("x is greater than 10\n");
      x++;
   } while(x > 10);
   
   return 0;
}
```

In this example, the variable `x` is initialized to 5. In the while loop, the condition is checked before the code block is executed. Since `x` is less than 10, the code block is never executed, and the loop terminates without any output.

In the do-while loop, the code block is executed at least once before the condition is checked. Since `x` is initially less than 10, the code block is executed once and then the condition is checked. Since `x` is still less than 10, the loop terminates and the output is:

```c
While loop:
Do-while loop:
x is greater than 10
``` 

As you can see, the while loop did not execute the code block at all, while the do-while loop executed the code block at least once before checking the condition.

### 4. Define a function? List out the categories of functions with example program (10M)
**Ans:** In programming, a function is a block of code that performs a specific task. It can be called multiple times from different parts of a program to avoid code repetition and make the code more modular. A function may or may not return a value.

Here's an example program in C language that demonstrates how to define and use functions:

```c
#include <stdio.h>

// Function to calculate the sum of two integers
int sum(int a, int b) {
   return a + b;
}

// Function to print a message
void print_message() {
   printf("Hello, world!\n");
}

int main() {
   // Calling the sum function
   int result = sum(5, 10);
   printf("Result of sum function: %d\n", result);
   
   // Calling the print_message function
   print_message();
   
   return 0;
}
```

In this example program, there are two functions: `sum` and `print_message`. The `sum` function takes two integers as input parameters and returns their sum as an integer value. The `print_message` function does not take any input parameters and does not return a value. It simply prints a message to the console.

Functions can be categorized based on their return type and the number of input parameters they take. Here are some common categories of functions in C language:

1. Function with no return value and no input parameters:
```c
void print_message() {
   printf("Hello, world!\n");
}
```

2. Function with no return value but with input parameters:
```c
void print_name(char *name) {
   printf("Hello, %s!\n", name);
}
```

3. Function with a return value but with no input parameters:
```c
int get_random_number() {
   return rand() % 100;
}
```

4. Function with a return value and with input parameters:
```c
int sum(int a, int b) {
   return a + b;
}
```

Functions can also be further classified based on their scope and visibility. However, these are more advanced topics and not relevant for this basic introduction to functions in C.
### 5(a)   Explain the construction of loops with basic programming constructs. (5M)

**Ans:** In programming, a loop is a structure that allows you to repeat a block of code multiple times. There are different types of loops, but the most common ones are the "for" loop and the "while" loop.

Here's how you can construct loops using basic programming constructs:

1. For loop:
A for loop is used to iterate over a sequence of values. The basic syntax of a for loop is as follows:

```c
for variable in sequence:
	# block of code to be executed
```

The "variable" is assigned the first value in the "sequence", and the block of code is executed. Then the "variable" is assigned the next value in the "sequence", and the block of code is executed again, and so on until the end of the "sequence" is reached.

Example:
```c
for i in range(5):
	print(i)
```

Output:
```
0
1
2
3
4
```

2. While loop:
A while loop is used to repeat a block of code as long as a certain condition is true. The basic syntax of a while loop is as follows:

```c
while condition:
	# block of code to be executed
```

The "condition" is evaluated first, and if it is true, the block of code is executed. Then the "condition" is evaluated again, and if it is still true, the block of code is executed again, and so on until the "condition" is false.

Example:
```c
i = 0
while i < 5:
	print(i)
	i += 1
```

Output:
```c
0
1
2
3
4
```

In this example, the block of code is executed as long as the variable "i" is less than 5. The variable "i" is incremented by 1 in each iteration of the loop.



### 5(b)   Write a c program to perform arithmetic operations using switch statement    (5M)

**Ans:** Here's an example program in C that performs arithmetic operations using a switch statement:

```c
#include <stdio.h>

int main() {
	char operator;
	double operand1, operand2, result;

	printf("Enter an operator (+, -, *, /): ");
	scanf("%c", &operator);

	printf("Enter two operands: ");
	scanf("%lf %lf", &operand1, &operand2);

	switch(operator) {
    	case '+':
        	result = operand1 + operand2;
        	printf("%.2lf + %.2lf = %.2lf", operand1, operand2, result);
        	break;
    	case '-':
        	result = operand1 - operand2;
        	printf("%.2lf - %.2lf = %.2lf", operand1, operand2, result);
        	break;
    	case '*':
        	result = operand1 * operand2;
        	printf("%.2lf * %.2lf = %.2lf", operand1, operand2, result);
        	break;
    	case '/':
        	result = operand1 / operand2;
        	printf("%.2lf / %.2lf = %.2lf", operand1, operand2, result);
        	break;
    	default:
        	printf("Invalid operator");
	}

	return 0;
}
```

In this program, we first declare variables for the operator, operands, and result. We then prompt the user to enter an operator and two operands using the `printf` and `scanf` functions.

Next, we use a `switch` statement to perform the appropriate arithmetic operation based on the operator entered by the user. The result of the operation is stored in the `result` variable.

Finally, we print the result using `printf` and return 0 to indicate successful program execution.

Note: This program assumes that the user enters valid input. In a real-world scenario, you should include error checking to handle cases where the user enters invalid input.

### 6(a)  Explain about program design and implementation issues in problem solving (5M).

**Ans:** Program design and implementation issues are important considerations in problem solving as they affect the quality, efficiency, and maintainability of a solution.

Here are some key aspects of program design and implementation issues that should be considered:

1. Understanding the problem:
Before designing a program, it is important to thoroughly understand the problem that needs to be solved. This includes understanding the inputs, outputs, constraints, and desired behavior of the program. A clear understanding of the problem can help in choosing appropriate algorithms and data structures to solve the problem efficiently.

2. Choosing appropriate algorithms and data structures:
Choosing the right algorithms and data structures is essential for creating an efficient and effective program. This involves evaluating various options and selecting the one that is most appropriate for the problem at hand. Factors that may influence this decision include the size and complexity of the problem, the available computing resources, and the desired output format.

3. Breaking down the problem into smaller sub-problems:
Breaking down a complex problem into smaller sub-problems can help make the problem more manageable and easier to solve. Each sub-problem can be tackled individually, with the results combined to solve the larger problem. This can also help in identifying areas where optimization is possible.

4. Planning the program structure:
Once the problem has been analyzed and the algorithms and data structures chosen, it is important to plan the structure of the program. This involves deciding on the programming language, breaking down the program into modules or functions, and deciding how data will be passed between them.

5. Implementation:
Implementation involves writing the actual code for the program. This should be done with careful attention to detail, ensuring that the code is correct, efficient, and easy to read and understand. Documentation and commenting should be included as appropriate, to aid in maintenance and future development.

6. Testing and debugging:
Testing and debugging are important steps in ensuring that the program is correct and free of errors. This involves running the program with test cases, analyzing the output, and making necessary corrections. This process should be repeated until the program performs as expected.

7. Maintenance and updates:
Once a program has been developed and deployed, it is important to maintain and update it as needed. This may involve fixing bugs, adding new features, or optimizing the program for better performance. Good documentation, commenting, and modularity can make these tasks easier and more efficient.

In summary, program design and implementation issues are crucial to problem-solving as they can impact the quality, efficiency, and maintainability of a solution. A well-designed and well-implemented program can help solve problems more effectively and with greater efficiency.

### 6(b)   Explain about parameter passing techniques in detail .                              (5M)

**Ans:** In computer programming, parameter passing is the mechanism by which a function or procedure can accept inputs (arguments) and return outputs (results). There are several different techniques for passing parameters between functions, each with its own advantages and disadvantages. Here are the most common parameter passing techniques:

1. Pass by value:
In pass by value, the function receives a copy of the value of the parameter. Any changes made to the parameter within the function have no effect outside the function. This method is simple and efficient, but it is not suitable for passing large data structures or arrays.

2. Pass by reference:
In pass by reference, the function receives a reference to the actual memory location of the parameter. This allows the function to modify the value of the parameter, which will also affect the value of the original variable outside the function. This method is useful for passing large data structures or arrays, but it can be more complex to implement.

3. Pass by pointer:
In pass by pointer, the function receives a pointer to the memory location of the parameter. This is similar to pass by reference, but the syntax is slightly different. This method is useful for passing large data structures or arrays and can be more efficient than pass by reference, but it can also be more error-prone if not implemented correctly.

4. Pass by name:
In pass by name, the parameter is replaced by its value every time it is accessed within the function. This method can be used for lazy evaluation, where the parameter is only evaluated if it is actually used within the function. However, it can also lead to unexpected behavior if the value of the parameter changes during execution.

5. Pass by const reference:
In pass by const reference, the function receives a reference to the memory location of the parameter, but the value of the parameter cannot be modified. This is useful for ensuring that the original value of the parameter is not accidentally changed within the function.

6. Pass by default:
In pass by default, the function has default values assigned to the parameters. This allows the function to be called with fewer arguments, and the default values are used for any parameters that are not provided. This method is useful for functions with optional parameters.

In summary, parameter passing techniques are a crucial part of programming, as they allow functions to communicate with each other and process inputs and outputs. The choice of parameter passing technique depends on the nature of the function, the size and type of the parameters, and the desired behavior of the program.

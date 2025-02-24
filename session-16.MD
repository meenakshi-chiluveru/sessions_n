When executing commands in a shell environment, each command returns a status code that indicates the outcome of its execution. This status is represented by the special variable `$?`. A status code of 0 signifies that the command completed successfully without any errors, while any non-zero value indicates that an issue occurred during its execution. Understanding these status codes is essential for effective shell scripting and debugging, as they provide insight into the success or failure of commands run in the terminal.

To determine whether a particular condition has resulted in success or failure, one can utilize the `if` statement, a fundamental construct in programming.

### Basic Condition Check:
```bash
if condition; then
    # Commands to execute if the condition is true
fi
```
In this structure, the code within the `then` block runs only if the specified condition evaluates to true.

### Conditional Execution with Else:
```bash
if condition; then
    # Commands to execute if the condition is true
else
    # Commands to execute if the condition is false
fi
```
This extended format introduces an `else` clause, allowing for an alternate set of commands to execute when the condition is false, providing a clear path for both scenarios.

### Handling Multiple Conditions with Else-If:
```bash
if [expression1]; then
    # Commands to execute if expression1 is true
elif [expression2]; then
    # Commands to execute if expression2 is true
else
    # Commands to execute if neither expression1 nor expression2 is true
fi
```
The else-if construct enables the evaluation of multiple conditions in sequence. If the first condition (`expression1`) is true, its corresponding commands execute; if not, the program checks the second condition (`expression2`). If neither condition is met, the commands within the `else` block are executed, offering a structured way to handle various possibilities.

These conditional structures allow for sophisticated decision-making in scripts, ensuring the appropriate commands are executed based on the outcome of specified conditions.

In conditional statements, the expressions being evaluated can involve various types of data, including numbers, strings, or files. 

### Numeric Condition Expressions
When dealing with numerical comparisons, several operators can be employed to assess relationships between values. Here are some examples:

- `1 -eq 2`: Evaluates whether 1 is equal to 2.
- `1 -ne 2`: Checks if 1 is not equal to 2.
- `1 -lt 2`: Determines if 1 is less than 2.
- `1 -gt 2`: Verifies if 1 is greater than 2.
- `1 -le 3`: Assesses whether 1 is less than or equal to 3.
- `1 -ge 7`: Tests if 1 is greater than or equal to 7.

### String Condition Expressions
For string comparisons, we utilize specific operators to identify relationships between strings. These include:

- `[ABC == ABC]`: Checks if the string 'ABC' is equal to 'ABC'.
- `abc != abc`: Verifies if the string 'abc' is not equal to 'abc'.
- `-z '$var'`: Determines if the variable `$var` is an empty string.

### File Condition Expressions
In scenarios where we need to assess the existence or properties of files, we can use file condition expressions. For instance:

- `[-e /opt/file]`: Checks if the file located at `/opt/file` exists.

This expanded explanation enriches the context of each type of expression, providing a clearer understanding of how they function and the conditions they evaluate.

if there is failure in execution then we will stop the executing by exit



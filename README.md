# Operation Class
The **'Operation'** class is a simple Java class that performs basic arithmetic operations on two numbers.

## Table of Contents
Introduction
Usage
Methods
Example
License
## Introduction
The **'Operation'** class is designed to perform common arithmetic operations such as addition, subtraction, multiplication, and division on two integers. It provides methods to retrieve the input numbers and the results of these operations.

## Usage
To use the **'Operation'** class, follow these steps:

 ### 1.Instantiate the class:
```bash
Operation operation = new Operation(num1, num2);
```
### 2.Perform operations:
Use the various methods to perform different arithmetic operations.

```bash
int sum = operation.addResult();
int difference = operation.subResult();
int product = operation.mulResult();
int quotient = operation.divResult();
```
### 3.Retrieve input numbers:

```bash
int firstNumber = operation.returnFirst();
int secondNumber = operation.returnSecond();
```

## Methods
**'returnFirst()'**: Returns the first input number.

**'returnSecond()'**: Returns the second input number.

**'addResult()'**: Returns the result of the addition operation.

**'subResult()'**: Returns the result of the subtraction operation.

**'mulResult()'**: Returns the result of the multiplication operation.

**'divResult()'**: Returns the result of the division operation.
## Example
```bash
public static void main(String[] args) {
    Operation operation = new Operation(10, 5);

    System.out.println("First Number: " + operation.returnFirst());
    System.out.println("Second Number: " + operation.returnSecond());
    System.out.println("Sum: " + operation.addResult());
    System.out.println("Difference: " + operation.subResult());
    System.out.println("Product: " + operation.mulResult());
    System.out.println("Quotient: " + operation.divResult());
}
```
## License
This project is licensed under the MIT License.

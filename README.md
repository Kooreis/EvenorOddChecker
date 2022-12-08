# Python Documentation

# Python Number Checker

This Python script is a simple program that checks if a given number is even or odd.

## Description

The script prompts the user to input a number. It then checks if the number is even or odd by using the modulus operator. If the number is divisible by 2 with no remainder, it is even. Otherwise, it is odd. The result is then printed out to the console.

## Usage

To use this script, simply run it in a Python environment. You will be prompted to enter a number. After entering a number, the script will print out whether the number is even or odd.

## Code Explanation

```python
def check_number():
    num = int(input("Enter a number: "))
    if (num % 2) == 0:
        print("{0} is Even".format(num))
    else:
        print("{0} is Odd".format(num))

check_number()
```

- `def check_number():` This line defines a function called `check_number`.
- `num = int(input("Enter a number: "))` This line prompts the user to enter a number. The input is converted to an integer and stored in the variable `num`.
- `if (num % 2) == 0:` This line checks if the number is even. If the number divided by 2 has no remainder, then the number is even.
- `print("{0} is Even".format(num))` If the number is even, this line prints out that the number is even.
- `else:` If the number is not even (i.e., it's odd), the script moves to the next line.
- `print("{0} is Odd".format(num))` If the number is odd, this line prints out that the number is odd.
- `check_number()` This line calls the function `check_number`, which starts the script.

## Libraries

This script does not use any imported libraries. It only uses built-in Python functions.

---

# C# Documentation

# CSharp Even or Odd Number Checker

This is a simple C# script that checks if a number entered by the user is even or odd.

## Script Description

The script prompts the user to enter a number. It then checks if the number is even or odd by using the modulus operator. If the number is divisible by 2 with no remainder, it is even. Otherwise, it is odd. The result is then displayed to the user.

## Code Breakdown

```csharp
using System;
```
The `System` namespace contains fundamental classes and base classes that define commonly-used value and reference data types, events and event handlers, interfaces, attributes, and processing exceptions. In this script, it is used to handle standard I/O operations through the `Console` class.

```csharp
class Program
{
    static void Main(string[] args)
    {
```
This is the main entry point for the program. The `Main` method is the entry point of a C# console application or windows application. When the application is started, the `Main` method is the first method that is invoked.

```csharp
        Console.Write("Enter a number: ");
        int number = Convert.ToInt32(Console.ReadLine());
```
The `Console.Write` method is used to display a message to the user. `Console.ReadLine` is then used to read the user's input. The input is expected to be a number, so it is converted from string to integer using `Convert.ToInt32`.

```csharp
        if (number % 2 == 0)
        {
            Console.WriteLine("The number is even.");
        }
        else
        {
            Console.WriteLine("The number is odd.");
        }
    }
}
```
The script then checks if the number is even or odd by using the modulus operator (`%`). If the number is divisible by 2 with no remainder, it is even. Otherwise, it is odd. The result is then displayed to the user using `Console.WriteLine`.

---

# Java Documentation

# Java Even or Odd Number Checker

This is a simple Java program that checks if a number entered by the user is even or odd.

## Description

The program prompts the user to enter a number. It then checks if the number is even or odd by using the modulus operator. If the number is divisible by 2 with no remainder, it is even. Otherwise, it is odd. The result is then printed out to the console.

## Libraries Used

### java.util.Scanner

This is a Java utility class that is used to read input from different sources like input streams and the user input from the console. In this program, it is used to read the number entered by the user from the console.

## Code Explanation

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter a number:");
        int num = scanner.nextInt();
        if (num % 2 == 0) {
            System.out.println("The number is even");
        } else {
            System.out.println("The number is odd");
        }
    }
}
```

- `Scanner scanner = new Scanner(System.in);` - This line creates a new Scanner object that reads from the System input stream (in this case, the console).
- `System.out.println("Enter a number:");` - This line prints a message to the console asking the user to enter a number.
- `int num = scanner.nextInt();` - This line reads the next integer entered by the user and assigns it to the variable `num`.
- `if (num % 2 == 0) {...} else {...}` - This is an if-else statement that checks if the number is even or odd. If the number is divisible by 2 with no remainder (`num % 2 == 0`), it is even and the message "The number is even" is printed to the console. Otherwise, the message "The number is odd" is printed.

---

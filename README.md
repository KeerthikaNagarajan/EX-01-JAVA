## Ex-01:
## Java program to print the Arithmetic operations
### AIM:
To write a java program to print the Arithmetic operations like Addiction, Subtraction, Division, Remainder of two numbers.

### ALGORITHM:
* Import required packages.
* Declare main method with the signature "public static void main(String[] args)".
* Get two numbers as input.
* Perform operations like addition,subtraction,multiplication,division and modulus using the two inputs.
* Print the output on display.

### PROGRAM:
```
import java.util.Scanner;
public class Ex1
{
    public static void main(String[] args)
    {
        Scanner num = new Scanner(System.in);
        System.out.println("Enter two numbers:");
        int num1 = num.nextInt();
        int num2 = num.nextInt();
        System.out.println("Sum of two numbers: "+(num1+num2));
        System.out.println("Multiplication of two numbers: "+(num1*num2));
        System.out.println("Subtraction of two numbers: "+(num1-num2));
        System.out.println("Division of two numbers: "+(num1/num2));
        System.out.println("Reminder of two numbers: "+(num1%num2));
    }
}
```

### OUTPUT:
<img width="224" alt="image" src="https://github.com/KeerthikaNagarajan/Java-Ex-1/assets/93427089/e0ded2a0-7874-4837-9830-5409af3973a2">

### RESULT:
The java program to print the Arithmetic operations like Addiction, Subtraction, Division, Remainder of two numbers was successfully done.

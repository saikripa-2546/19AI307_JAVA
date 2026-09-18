# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object using a given string and assigns its reference to the variable sb.

## ALGORITHM :
1.	Start the program.
2.	Declare and initialize a string variable str1.
3.	Create a StringBuilder object by passing str1 to its constructor.
4.	Store the object reference in the variable sb.
5.	Print the contents of sb to verify the output.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: SAI KRIPA SK 
RegisterNumber:  212224040284
*/
```

## Sourcecode.java:

```
import java.util.Scanner;

public class StringBuilderAppend {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String input = scanner.nextLine();
        scanner.close();

        StringBuilder sb1 = new StringBuilder(input); // Initialize with input
        sb1.append("s");

        System.out.println("sb1 = " + sb1.toString());
    }
}
```







## OUTPUT:

<img width="305" height="135" alt="Screenshot 2026-09-17 172747" src="https://github.com/user-attachments/assets/c895d5a6-59cb-4057-99c0-059db0c96422" />


## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.


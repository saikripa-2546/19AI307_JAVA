# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to Find the Largest or Max Number in Array using has - a relationship.
## ALGORITHM :
1.	Start the program.
2.	Create a class ArrayData:
a.	Declare an integer array and a variable for size.
b.	Create a method to read array elements from the user.
3.	Create another class ArrayOperation:
a.	Create a method findMax() that accepts an ArrayData object.
b.	Loop through the array and find the largest element.
4.	In the main() method of a class Main:
a.	Create an object of ArrayData and read the input.
b.	Create an object of ArrayOperation and call findMax() by passing the ArrayData object.
5.	Display the largest number.
6.	End the program.



## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: SAIKRIPA SK 
RegisterNumber:  212224040284
*/
```

## Sourcecode.java:

```
import java.util.Scanner;
class fun{
    public static boolean isPal(String s)
    {   
        if(s.length() == 0 || s.length() == 1)
            return true; 
        if(s.charAt(0) == s.charAt(s.length()-1))
        
        return isPal(s.substring(1, s.length()-1));
        return false;
    }
}
public class ArrayProgram {
    public static void main(String[] args)
    {
        Scanner scanner = new Scanner(System.in);
        String string = scanner.nextLine();
        fun obj=new fun();
        if(obj.isPal(string))
            System.out.println(string + " is a palindrome");
        else
            System.out.println(string + " is not a palindrome");
    }
}
```







## OUTPUT:

<img width="887" height="343" alt="Screenshot 2026-09-17 174120" src="https://github.com/user-attachments/assets/455eca5c-787f-427c-9fbd-c53d2340d1f2" />


## RESULT:
Thus the java program to Find the Largest or Max Number in Array using has - a relationship was executed successfully. 

# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To Create a java program to print the sum of two number using getter and setter method.

## ALGORITHM :
1.  Start the Program
2.	Define class `Employee`:
-	a) Private variables `n1` and `n2`
-	b) Method `setsum(int n1, int n2)` to set values of `n1` and `n2`
-	c) Method `getsum()` to calculate and print `sum = n1 + n2`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integers `n1` and `n2`
-	b) Create ` Employee ` object, set values, and call `getsum()`
4.	End


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: SAIKRIPA SK 
RegisterNumber:  212224040284
*/
```

## Sourcecode.java:


```
import java.util.*;
public class SetAndGet {
 
 private int w;
 private int h;


public int getWidth() {
 return w;
}

public void setWidth(int w) {
 this.w = w;
}

public int getHeight() {
 return h;
}

public void setHeight(int h) {
 this.h = h;
}


public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 int s1=sc.nextInt();
 int s2=sc.nextInt();
 
 obj.setWidth(s1);
 obj.setHeight(s2);
 System.out.println(obj.getWidth() * obj.getHeight());

}


}
```






## OUTPUT:

<img width="270" height="240" alt="Screenshot 2026-09-17 173852" src="https://github.com/user-attachments/assets/fc642279-868a-4b06-9d41-c113b166c1f0" />


## RESULT:
Thus the java program to print the sum of two number using getter and setter method was executed successfully.






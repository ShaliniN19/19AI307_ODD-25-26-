# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
<img width="503" height="206" alt="image" src="https://github.com/user-attachments/assets/e69ccab1-d8a0-4953-9a9e-33ffa05a7007" />


## AIM:
To develop a Java program that calculates the factorial of a non-negative integer using a for loop and displays the result.

## ALGORITHM :
1.	Start the program. Read a non-negative integer n from the user.
2.	 Initialize a variable factorial to 1. Check if n is 0.
3.	 If yes, set factorial as 1. Otherwise, use a for loop from 1 to n.
4.	  Multiply factorial by each number in the loop. Store the final product in factorial.
5.	  Display the factorial of the given number.
6.	  Stop the program.





## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: SHALINI N
RegisterNumber:  212224040305
*/
```

## SOURCE CODE:

```
import java.util.Scanner;
public class Main{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        long factorial = 1;
        if(n<0){
            System.out.println("please give me valid number");
        }
        else{
            for(int i=1;i<=n;i++){
                factorial *= i;
            }
            System.out.println("Factorial of "+n+" is: "+factorial);
        }
    }
}
```





## OUTPUT:
<img width="403" height="167" alt="image" src="https://github.com/user-attachments/assets/1a030cf7-452b-4bf6-a19b-f41404e8a759" />



## RESULT:
Thus, the Java program to calculate the factorial of a non-negative integer using a for loop was implemented and executed succ

# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
<img width="313" height="191" alt="image" src="https://github.com/user-attachments/assets/fe6b54ae-aab8-4ab1-b825-345966295d03" />


## AIM:
TO study and implement conditional statements in Java (if, if-else, else-if ladder, and switch) for decision-making based on given conditions.
## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Declare the required variables. Accept input values from the user.
4.	Evaluate the given condition using a conditional statement.
5.	If the condition is true, execute the corresponding block of statements.
6.	If the condition is false, execute the alternative block of statements.
7.	For multiple conditions, use an else-if ladder or switch statement.
8.	Display the appropriate result based on the evaluated condition.
9.	Stop the program.





## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: Shalini N
RegisterNumber:  212224040305
*/
```

## SOURCE CODE:

```
import java.util.Scanner;
public class Main{
    public static void main(String[] args){
        Scanner sc= new Scanner(System.in);
        int n = sc.nextInt();
        if(n%2==0){
            if(n<100){
                System.out.println("Weak Code");
            }
            else if(n>=100 && n<=999){
                System.out.println("Strong Code");
            }
            else{
                System.out.println("Access Denied");
            }
        }
        else{
            System.out.println("Access Denied");
        }
    }
}
```





## OUTPUT:
<img width="504" height="188" alt="image" src="https://github.com/user-attachments/assets/995fc334-f0d4-4c30-ac3a-bd956a49eb28" />



## RESULT:
Thus, the Java program using conditional statements was implemented and executed successfully, and the desired output was obtained based on the given conditions.

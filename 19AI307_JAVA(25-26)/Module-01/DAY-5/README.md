# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
<img width="238" height="78" alt="image" src="https://github.com/user-attachments/assets/aede5a67-b8f2-4d1a-bdaa-b9c454527aec" />


## AIM:
To develop a Java program that reverses a given string and displays the reversed string.

## ALGORITHM :
1.	Start the program.
2.	Read the input string from the user.
3.	Initialize an empty string to store the reversed string.
4.	Traverse the original string from the last character to the first character.
5.	Append each character to the reversed string. Display the reversed string.
6.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: SHALINI N
RegisterNumber: 212224040305
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String str = sc.nextLine();
        String rev = "";

        for (int i = str.length() - 1; i >= 0; i--) {
            rev += str.charAt(i);
        }

        System.out.println("Reversed string: " + rev);

        sc.close();
    }
}
```






## OUTPUT:

<img width="375" height="167" alt="image" src="https://github.com/user-attachments/assets/dfef2301-0827-4f47-b3cc-fdce4b95e8e0" />


## RESULT:
Thus, the Java program to reverse a given string was implemented and executed successfully.

# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
<img width="504" height="347" alt="image" src="https://github.com/user-attachments/assets/4875f56c-9d21-439f-b470-6d25124d7d2b" />



## AIM:
To develop a Java program that accepts values of different data types from the user and displays them using appropriate Java data types.

## ALGORITHM :
1.	Start the program
2.	Create a Scanner object to read input from the use
3.	Read a value of type byte.
4.	Read a value of type short.
5.	Read a value of type int.
6.	Read a value of type long.
7.	Read a value of type float. 
8.Read a value of type double.
9.Read a value of type boolean. Read a value of type char. Read a value of type String.
10.Display a heading message. Print all the values along with their respective data type names.
11.Stop the program.




## PROGRAM:
```
/*
Program to implement a Synchronization concept using Java
Developed by: Shalini N
RegisterNumber: 212224040305
*/
```

## Sourcecode.java:
 ```
import java.util.Scanner;

public class main{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        byte b = sc.nextByte();
        short s = sc.nextShort();
        int i = sc.nextInt();
        long l = sc.nextLong();
        float f = sc.nextFloat();
        double d = sc.nextDouble();
        boolean bool = sc.nextBoolean();
        char c = sc.next().charAt(0);
        sc.nextLine();
        String str = sc.nextLine();

        System.out.println("Hey Lovely, let's print all types of data received from user using different data types");
        System.out.println("This is byte datatype " + b);
        System.out.println("This is short datatype " + s);
        System.out.println("This is int datatype " + i);
        System.out.println("This is long datatype " + l);
        System.out.println("This is float datatype " + f);
        System.out.println("This is double datatype " + d);
        System.out.println("This is boolean datatype " + bool);
        System.out.println("This is char datatype " + c);
        System.out.println("This is string datatype " + str);
        
    }
}
```









## OUTPUT:
<img width="499" height="208" alt="image" src="https://github.com/user-attachments/assets/88a94fa1-609a-473d-8907-69969a42baa6" />



## RESULT:
Thus, the Java program to accept and display values of different data types was implemented and executed successfully.

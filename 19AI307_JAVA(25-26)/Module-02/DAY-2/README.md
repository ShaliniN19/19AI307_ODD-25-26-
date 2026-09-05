# Ex.No:2(B) METHODS

## QUESTION:
<img width="503" height="217" alt="image" src="https://github.com/user-attachments/assets/392f5ff5-11da-45b8-8ca5-f45de5b84738" />


## AIM:
To develop a Java program that uses an instance method calculateSum() to calculate and return the sum of elements in an integer array.

## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Create an integer array of the given size.
4.	Read the array elements. Create an object of the ArrayOps class.
5.	Call the calculateSum() method and pass the array as an argument.
6.	Inside the method, initialize sum to 0. Traverse the array and add each element to sum.
7.	Return the value of sum. Print the returned result.
8.	Stop the program.


## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: SHALINI N
RegisterNumber: 212224040305
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class ArrayOps {

    
    public int calculateSum(int[] arr) {
        int sum = 0;
        for (int num : arr) {
            sum += num;
        }
        return sum;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int n = sc.nextInt();
        int[] arr = new int[n];
        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }

        ArrayOps obj = new ArrayOps();
        int result = obj.calculateSum(arr);
        System.out.println(result);

        sc.close();
    }
}
```






## OUTPUT:

<img width="289" height="142" alt="image" src="https://github.com/user-attachments/assets/34c77681-a165-4d22-92bb-859552666699" />


## RESULT:
Thus, the Java program to find the sum of elements in an integer array using an instance method was implemented and executed successfully.

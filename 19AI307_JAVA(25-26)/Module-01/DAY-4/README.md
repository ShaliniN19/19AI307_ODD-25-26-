# Ex.No:1(D) ARRAYS

## QUESTION:
<img width="271" height="164" alt="image" src="https://github.com/user-attachments/assets/2faaf54b-d38d-4e89-9375-4ebcb44d22ee" />


## AIM:
To develop a Java program that calculates the average of the elements in an array and displays the result.

## ALGORITHM :
1.	Start the program.
2.	Read the number of elements n in the array.
3.	Declare an array of size n. Initialize a variable sum to 0.
4.	Read the array elements from the user.
5.	Add each element to sum.





## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: SHALINI N
RegisterNumber:  212224040305
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int n = sc.nextInt();
        int[] arr = new int[n];
        int sum = 0;

        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
            sum += arr[i];
        }

        double average = (double) sum / n;

        System.out.printf("The average of elements is %.2f", average);

        sc.close();
    }
}
```





## OUTPUT:

<img width="486" height="291" alt="image" src="https://github.com/user-attachments/assets/1220b5aa-2984-4fb5-a46d-78531e7565f9" />


## RESULT:
Thus, the Java program to find the average of array elements was implemented and executed successfully.

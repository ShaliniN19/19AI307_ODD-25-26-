# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
<img width="409" height="107" alt="image" src="https://github.com/user-attachments/assets/9a53482e-2a5f-4753-b790-580f327afd14" />


## AIM:
To create a Java class Car with attributes brand, model, and year, create two objects of the class, and print their details.

## ALGORITHM :
1.Start the program.
2.Create a class named Car. 
3.Declare the attributes brand, model, and year. 
4.Create a constructor to initialize these attributes. 
5.Create two Car objects with different values. 
6.Access the attributes of each object. 
7.Print the details of both cars. 
8.Stop the program.





## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: SHALINI N
RegisterNumber:  212224040305
*/
```

## SOURCE CODE:

```
class Car{
        String brand;
        String model;
        int year;
    }
public class prog {
    public static void main(String[] args) {
        Car car1 = new Car();
        car1.brand = "Toyota";
        car1.model = "Innova";
        car1.year = 2022;

        Car car2 = new Car();
        car2.brand = "Hyundai";
        car2.model = "i20";
        car2.year = 2021;

        System.out.println("Car 1: " + car1.brand + " " + car1.model + " " + car1.year);
        System.out.println("Car 2: " + car2.brand + " " + car2.model + " " + car2.year);
    }
}
```





## OUTPUT:
<img width="331" height="132" alt="image" src="https://github.com/user-attachments/assets/785ad99f-8e2b-4aa4-bb2c-75a36bc2fc04" />



## RESULT:
Thus, the Java program to create a Car class, instantiate two objects, and print their details was implemented and executed successfully.

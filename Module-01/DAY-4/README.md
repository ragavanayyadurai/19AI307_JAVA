# Ex.No:1(D) User Defined Method

## AIM:
Write a Java program to print Student details (name, age) age is same to all members in the class. Use static type variable to access age.


## ALGORITHM :
1. Start the program and define a class Main with variables: name (String) and age (int, initialized to 18).
2. In the main method, create a Scanner object to take input from the user.
3. Create two instances of the Main class: obj1 and obj2.
4. Use the scanner to input names for obj1 and obj2.
5. Print the name and age of both obj1 and obj2 using System.out.println.
6. End the program.



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: RAGAVENDRAN A
RegisterNumber: 212222230114
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main
{
    String name;
    int age=18;
    public static void main(String[] args){
    Scanner sc = new Scanner(System.in);
	Main obj1=new Main();
	Main obj2=new Main();
	obj1.name=sc.next();
	obj2.name=sc.next();
	System.out.println("Student name: "+obj1.name+"Age: "+obj1.age);
	System.out.println("Student name: "+obj2.name+"Age: "+obj2.age);

}
}

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/157cbc10-975d-4f68-ab5e-5fc6d0e511db)




## RESULT:
Thus the java program for Student details (name, age) age is same to all members in the class was executed successfully.



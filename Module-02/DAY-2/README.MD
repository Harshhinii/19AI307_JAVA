# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
To develop a Java Program to display the addition number using private modifiers only.

## ALGORITHM :
1.	Start the program.
2.	Define a class named `addition`
3.	Declare two private integer variables, `num1` and `num2`
4.	Define a private method `add()` that:
a)	Returns the sum of `num1` and `num2`
5.	Define a public method `display(int n1, int n2)` that:
a)	Assigns `n1` to `num1` and `n2` to `num2`
b)	Calls the `add()` method and prints the result using `System.out.println`
6.	Define the `main` method as static
a)	Create an instance of the `addition` class called `ad`
b)	Call the `display(8, 9)` method on the `ad` object
7.	End






## PROGRAM:
 ```
/*
Program to implement a access modifiers using Java
Developed by: Harshini R
RegisterNumber: 212223220033 
*/
```
## SOURCE CODE:
```
import java.util.Scanner;

class Employee {
    String name;

    void setName(String name) {
        this.name = name;  
    }

    Employee display() {
        return this;  
    }

    void printName() {
        System.out.println("Employee Name: " + name);
    }
}

class prog {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String inputName = scanner.nextLine();

        Employee emp = new Employee();
        emp.setName(inputName);
        emp.display().printName();  
    }
}
```


## OUTPUT:

<img width="686" height="326" alt="image" src="https://github.com/user-attachments/assets/954fafa4-a638-4044-b666-3322017194cd" />


## RESULT:
Thus , the program was executed Successfully.



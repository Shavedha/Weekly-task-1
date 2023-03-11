# Weekly-task-1
### 1. Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int add,sub,prod,rem;
        float divide;
        Scanner sc = new Scanner(System.in);
        int ab=sc.nextInt();
        int cd=sc.nextInt();
        add=ab+cd;
        sub=ab-cd;
        prod=ab*cd;
        divide=ab/cd;
        rem=ab%cd;
        System.out.println("Sum = "+add);
        System.out.println("Subtraction = "+sub);
        System.out.println("Product = "+prod);
        System.out.println("Division = "+divide);
        System.out.println("Remainder = "+rem);

    }
}
```
<img width="487" alt="image" src="https://user-images.githubusercontent.com/93427376/224482264-562fb308-63af-4499-87ea-501982c6662b.png">

### 2. Write a Java program to compare two numbers
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int ab=sc.nextInt();
        int cd=sc.nextInt();
        if(ab==cd)
            System.out.println(ab+"=="+cd);
        else if(ab>cd)
            System.out.println(ab+">"+cd);
        else if(ab<cd)
            System.out.println(ab+"<"+cd);
        else if(ab!=cd)
            System.out.println(ab+"is not equal to"+cd);

    }
}
```
<img width="347" alt="Screenshot 2023-03-10 184537" src="https://user-images.githubusercontent.com/93427376/224482549-2b21b30b-a520-4324-8130-62f63f8cb377.png">

### 3.Write a Java program to convert a string to an integer
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int num=Integer.valueOf("-7645");
        System.out.println("Number is = "+num);
    }
}
```
<img width="349" alt="Screenshot 2023-03-10 185659" src="https://user-images.githubusercontent.com/93427376/224482715-53ee55e1-3717-4895-91ef-b20f067a1864.png">

### 4.Java Program to find area of rhombus
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter Diagonal 1: ");
        int d1=sc.nextInt();
        System.out.println("Enter Diagonal 2: ");
        int d2=sc.nextInt();
        int Area=(d1*d2)/2;
        System.out.println("Area of Rhombus = "+Area);
    }
}
```
<img width="425" alt="Screenshot 2023-03-10 190755" src="https://user-images.githubusercontent.com/93427376/224482887-e23dee96-ca01-4ed5-b0a9-8e945b4c23b7.png">

### 5.Write a Java program to find the number of days in a month
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int month;
        System.out.println("Enter month number from 1(-Jan) to 12(-Dec): ");
        month=sc.nextInt();
        if(month==1||month==3||month==5||month==7||month==8||month==10||month==12){
            System.out.println("31 Days in this Month");
        }
        else if(month==4||month==6||month==7||month==11){
            System.out.println("30 Days in this Month");
        }
        else if(month==2){
            System.out.println("28 Days in this Month");
        }
        else{
            System.out.println("Enter a valid number from 1 to 12");
        }
    }
}
```
<img width="529" alt="Screenshot 2023-03-10 193110" src="https://user-images.githubusercontent.com/93427376/224483202-79902e94-1e9d-4a35-9118-d1af7154151b.png">

### 6.Write a Java program to print the even numbers from 1 to 20
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println("Even numbers from 1 to 20 are:");
        int i;
        for(i=1;i<=20;i++){
            if(i%2==0){
                System.out.println(i);
            }
        }
    }
}
```
<img width="379" alt="image" src="https://user-images.githubusercontent.com/93427376/224483431-af2da14e-895e-472c-9abd-025549538950.png">

### 7.Write a Java program to create a simple calculator
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the choice: 1.Add\n2. Subtract\n3.Multiply\n4.Divide\n");
        int ch=sc.nextInt();
        System.out.println("Enter the 1st number: ");
        int num1=sc.nextInt();
        System.out.println("Enter the 2nd number: ");
        int num2=sc.nextInt();
        if(ch==1){
            int add=num1+num2;
            System.out.println("Sum = "+add);
        }
        else if(ch==2){
            int sub=num1-num2;
            System.out.println("Difference = "+sub);
        }
        else if(ch==3){
            int mul=num1*num2;
            System.out.println("Product = "+mul);
        }
        else{
            int div=num1/num2;
            System.out.println("Division = "+div);
        }
    }
}
```
<img width="632" alt="Screenshot 2023-03-10 200258" src="https://user-images.githubusercontent.com/93427376/224483792-fc37622d-9154-48b7-9c43-2676a17f18cb.png">

### 8.Write a Java program to print multiplication table of given number
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the number: ");
        int num=sc.nextInt();
        int i;
        for(i=1;i<=10;i++){
            System.out.println("2 * "+i +" = "+(num*i));
        }
    }
}
```
<img width="422" alt="image" src="https://user-images.githubusercontent.com/93427376/224484108-859e1b13-35b4-46e5-a5a1-a1b69a9b244d.png">




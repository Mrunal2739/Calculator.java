# Calculator.java

import java.util.*;

 class Calculator{
 
   public static void main(String args[])
   { 
    Calculator obj = new Calculator();
    obj.Addition();
    obj.Subtraction();
    obj.Multiplication();
    obj.Division();
   }
   
   void Addition(){
     
     Scanner sc = new Scanner(System.in);
     System.out.println("Enter first number:");
     int a = sc.nextInt();
     
     System.out.println("Enter second number:");
     int b = sc.nextInt();
     
     int sum = a+b;
     System.out.println("Sum="+sum);
   }
   
   
 void Subtraction(){
     
     Scanner sc = new Scanner(System.in);
     System.out.println("Enter first number:");
     float a = sc.nextInt();
     
     System.out.println("Enter second number:");
     float b = sc.nextInt();
     
     float sub = a-b;
     System.out.println("Subtraction="+sub);
   }
void Multiplication(){
     
     Scanner sc = new Scanner(System.in);
     System.out.println("Enter first number:");
     int a = sc.nextInt();
     
     System.out.println("Enter second number:");
     int b = sc.nextInt();
     
     int product = a*b;
     System.out.println("Multiplication="+product);
   }
   void Division(){
     
     Scanner sc = new Scanner(System.in);
     System.out.println("Enter first number:");
     int a = sc.nextInt();
     
     System.out.println("Enter second number:");
     int b = sc.nextInt();
     
     int div = a/b;
     System.out.println("Division="+ div);
   }
}

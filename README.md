# java-02-sum-of-two-numbers
sum of two numbers

# method_1----
taking input before compiling 
public class main{
<br>
 public static void main(String[]args){
 <br>
 int a = 5;
 <br>
 int b= 6;
 <br>
 System.out.println(a+b);
 <br>
 }
 <br>
} 


# method_2----
taking input while compiling 

import java.util.*; // here we are importing the needs which are used for scanning and these are in the utility package

public class main{
<br>
public static void main(Strings[]args){
Scanner sc=new Scanner(System.in);
System.out.println("enter the two numbers");
int a = sc.nextInt();
int b = sc.nextInt();
System.out.println("the sum of two numbers are "+(a+b));
}
}




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
<br>
Scanner sc=new Scanner(System.in);
<br>
System.out.println("enter the two numbers");
<br>
int a = sc.nextInt();
<br>
int b = sc.nextInt();
<br>
System.out.println("the sum of two numbers are "+(a+b));
<br>
}
<br>
}




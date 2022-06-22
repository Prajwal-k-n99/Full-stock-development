# Full-stock-development
Java programs
1.Program to add 3 numbers
package com.company
public class main{
public static void main(String[]args){
System.out.println("The sum of three numbers is")
int num1 = 6;
int num2 = 8;
int num3 = 10;
int sum = num1 + num2 + num3;
System.out.println(sum);
}
}
2.Program to calculate cgpa
package com.company
public class main{
public static void main(String[]args){
float sub 1 = 45;
float sub 2 = 68;
float sub 3 = 83;
float cgpa = (sub1 + sub2 + sub3)/30;
System.out.println(cgpa);
}
}
3.Program to print name
package com.company
public class main{
public static void main(String[]args){
System.out.println("What is your name");
Scanner sc = new Scanner(System.in);
String name = sc.next();
System.out.println("Hello" + name + "have a good day");
}
}
Loops and Statements
1.Program for else if statement
package com.company;
public class main{
public static void main(String[]args){
int age;
Scanner sc = new Scanner(System.in);
age = sc.nextInt();
if(age>56){
System.out.println("You are experienced");
}
else if(age>46){
System.out.println("You are semi experienced");
}
else if(age>36){
System.out.println("You are semi semi experienced");
}
else{
System.out.println("You are not experienced");
}
}
}
2.Program to find year  entered is leap year or not
package com.company;
import java.util.scanner;
public class Leap year{
public static void main(String[]args){
int year;
Scanner a = new Scanner(System.in);
year = a.nextInt();
if(year%4==0){
System.out.println("This year is leap year");
}
else{
System.out.println("This year is not leap year");
}
}
}
3.Write a program to print the following pattern
****
***
**
*
package com.company;
public class main{
public static void main(String[]args){
int n=4;
for(int i=4;i<0;i--){
for(int j=0;j<i;j++){
System.out.print("*");
System.out.print("/n");
}
}
}
4.Program to sum first n even numbers
package com.company;
public class main{
public static void main(String[]args){
int n=5;
sum=0;
for(int i=0;i<n;i++){
sum = sum + 2*i;
}
System.out.println(sum);
}
}
5.Program to print multiplication table of a given number
package com.company;
public class main{
public static void main(String[]args){
int n=8;
for(int i=1;i<=10;i++){
System.out.printf("%d*%d=%d\n",n,i,n*i);
}
}
}
6.Program to print factorial of a given number
package com.company;
public class main{
public static void main(String[]args){
int n=6;
int i=1'
factorial =1;
while(i<=n){
factorial * = i;
i++;
}
Sysyem.out.println(sum);
}
}

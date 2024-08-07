1.Write a Java program to print "Hello, World!" to the console. 
 
Code:- 
package Assignment; 
 
public class HelloWorld { 
 
 	public static void main(String[] args) { 
 	 	System.out.println("Hello World!"); 
 	} 
 
 
2.Write a program to find the sum of two numbers entered by the user. 

Code:- 
package Assignment; import java.util.Scanner;    // package which is use to take input by user. public class SumOfTwo { 
 
 	public static void main(String[] args) { 
 	 	System.out.println("Enter your first number :"); 
 	 	Scanner sc=new Scanner(System.in);     //object declaration 
 	 	double fn=sc.nextDouble(); 
 
 	 	System.out.println("Enter your Second number :"); 
 	 	Scanner sca=new Scanner(System.in);  	 	double sn=sca.nextDouble(); 
 
 	 	double sum=fn+sn; 
 	 	System.out.println("sum of your enterd no :"+sum);   //to Display the sum. 
 	} 
} 
 
 
3.Write a Java program to check whether a given number is even or odd. 

Code:- 
package Assignment; import java.util.Scanner;    // package which is use to take input by user. public class HelloWorld { 
 
 	public static void main(String[] args) {  	 	System.out.println("Enter your no. :"); 
 	 	Scanner number=new Scanner(System.in); //object declaration 
 	 	int GivenNumber=number.nextInt(); 
  	 	if(GivenNumber %2 ==0)  //logic for even no. 
 	 	{ 
   System.out.println("Given no.is even :"+GivenNumber);}  //to print even no. 
 	 	else  
 	 	{ 
 	 	 	System.out.println("Given no.is odd :"+GivenNumber);  //to print odd no. 
 	 	} 
 	} 
} 
 

  
4.Write a java program to find greatest of 3 numbers.

Code:- 
package WorksOfClass; import java.util.Scanner;  //use to take input from user. public class GraterNo3 { 
 
 	public static void main(String[] args) { 
 	 	// TODO Auto-generated method stub 
 	 	System.out.println("enter first no"); 
 	 	Scanner sc1=new Scanner(System.in); //object declaration 
 	 	int fn=sc1.nextInt();  // call the object 
 
 	 	System.out.println("enter Second no"); 
 	 	int Sn=sc1.nextInt(); 
 
 	 	System.out.println("enter Third no"); 
 	 	int Tn=sc1.nextInt(); 
 	 	if(fn>Sn && fn>Tn) {  //logic to compare no. 
 no. 	 	 	System.out.println("your First no is Greater");  //to print 1st 
 	 	} 
 	 	else if(Sn>fn && Sn>Tn) { 
 no. 	 	 	System.out.println("your Second no is Greater"); //to print 2nd 
 	 	} 
 	 	if(Tn>Sn && Tn>fn) { 
 no. 	 	 	System.out.println("your Third no is Greater"); //to print 3rd 
 	 	} 
 	 	sc1.close(); 
 	} 	
 
} 
 
Output:- 
  
 
5.Write a program to implement a basic calculator that takes input and evaluates it. 
 
Code:- 
package Assignment; import java.util.Scanner;    // package which is use to take input by user. public class HelloWorld { 
 
 	public static void main(String[] args) { 
 	 	System.out.println("Enter your  first no. :"); 
 	 	Scanner number=new Scanner(System.in); //object declaration 
 	 	int num1=number.nextInt(); 
 
 	 	System.out.println("Enter your  Second no. :"); 
 	 	int num2=number.nextInt();  	 	int sum= num1+num2;  //addition logic  	 	int sub=num1-num2;   //substraction logic  	 	int mul=num1*num2;  //multiplication logic 
 	 	float div=num1/num2;  //division logic 
 
 	 	System.out.println("Addition of given no. "+ sum); 
 	 	System.out.println("Substration of given no. "+ sub); 
 	 	System.out.println("Multiplication of given no. "+ mul); 
 	 	System.out.println("Division of given no. "+ div); 
 
 	} 
} 
 
Output:- 
  
 
 
6.Write a Java program to check if a given number is prime or not.

Code:- 
package Assignment; import java.util.Scanner;    // package which is use to take input by user. public class HelloWorld { 
 
 	public static void main(String[] args) { 
 	 	Scanner sc = new Scanner(System.in); 
 	 	System.out.print("Enter a number to check  prime or not: "); 
 	 	int number = sc.nextInt();  	 	sc.close(); 
 
 	 	if (isPrime(number)) { 
 	 	 	System.out.println(number + " is a prime number."); 
 	 	}  
 	 	else 
 	 	{ 
 	 	 	System.out.println(number + " is not a prime number."); 
 	 	} 
 	} 
 
 	public static boolean isPrime(int num) { 
 
 	 	if (num <= 3) { 
 	 	 	return true; // 2 and 3 are prime numbers 
  	 
 	 	if (num % 2 == 0 || num % 3 == 0) { 
 	 	 	return false; // multiples of 2 and 3 are not prime 
 
 
 
} 
 
Output:- 
 
 
7.Create a Java program that compares two numbers and prints the larger one.

Code:- 
package Assignment; import java.util.Scanner;    // package which is use to take input by user. public class HelloWorld { 
 
 	public static void main(String[] args) { 
 	 	Scanner obj=new Scanner(System.in); //object declaration  	 	System.out.println("Enter your first number");  	 	double firstn=obj.nextDouble();  
 	 	 
 	 	System.out.println("Enter your Second number");  	 	double secondn=obj.nextDouble();  
 	 	if(firstn >secondn)  //logic for 1st no. grater 
 	 	{ 
 	 	 	System.out.println("First number is greater than second"); 
 	 	} 
 	 	else if (secondn > firstn) //logic for 2nd no.grater 
 	 	{ 
 	 	 	System.out.println("Second number is greater than first"); 
 	 	 	} 
 	 	else 
 	 	{ 
 	 	 	System.out.println(" Both numbers are equal to each other"); 
 	 	 	}  
 	 	 
 
 	} 
} 
 

 
8.Write a Java program that takes an age input from the user and determines if they are eligible to vote (considering the legal voting age).

Code:- 
package Assignment; import java.util.Scanner;    // package which is use to take input by user. public class HelloWorld { 
 
 	public static void main(String[] args) { 
 	 	Scanner vote=new Scanner(System.in); //object declaration 
 	 	System.out.	print	("Enter your age : "); 
 	 	int candidateage=vote.nextInt(); 
  	 	if(candidateage >=18)  //logic for vote age. 
 	 	{ 
 	 	 	System.out.println("you are eligible to vote"); //to print eligible 
 	 	} 
 	 	else 
 	 	{ 
 	 	 	System.out.println("you are  not eligible to vote"); //to print not eligible 
 	 	} 
 
 
 	} 
} 
 
Output:- 

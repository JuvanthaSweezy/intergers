# intergers
/*
 * Juvantha crawford
 */ 
  
import java.util.*;

public class intergers
{
public static void main(String[] args)
{
Scanner myInput = new Scanner(System.in);
//Deteriming variables
System.out.println("Please enter intergers from 1-9 numbers");

double num1 = myInput.nextDouble();

double num2 = myInput.nextDouble();
double addition = (num1 + num2);
double subtraction = (num1 - num2);
double subtraction2 = (num2 - num1);
double multiplication = (num1 * num2);
double division = ( num1 / num2);
double division2 =(num2 / num1);


//Output
System.out.println("this is your intergers multiplied" + "\n" + multiplication);
System.out.println("this is your intergers divided" + "\n" + division);
System.out.println("this is your intergers added" + "\n" + addition);
System.out.println("this is your intergers subtracted" + "\n" + subtraction);
System.out.println("this is your intergers subtracted" + "\n" + subtraction2);
System.out.println("this is your intergers divided" + "\n" + division2);


}//end main
}//end class

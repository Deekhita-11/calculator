# calculator
import java.util.Scanner;
public class Calculator{
    public static void main(String[] args){
        Scanner sc=new Scanner (System.in);
     System.out.println("enter the first number");
     int num1=sc.nextInt();
     System.out.println("enter the operator  +,-,*,/");
     char operator =sc.next().charAt(0);
     System.out.println("enter the second number");
     int num2=sc.nextint();
     int result;
     switch(operator){
        case'+':
            result=num1+num2;
            System.out.println(result);
            break;

        case '-':
         result=num1-num2;
         System.out.println(result);
         break;
         case '*':
         result=num1*num2;
         System.out.println(result);
         break;
         case '/':
         result=num1/num2;
         System.out.println(result);
         break;
         default :
         System.out.println("error");


     }
      sc.close();
        }
}

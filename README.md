import java.util.Scanner;

Public class JavaProb1
{
  public static void main(String[] args)
  { 
    double a b;
    Scanner scanner=new Scanner(System.in)
    System.out.print("Enter first number");
    a=scanner.nextDouble();
    System.out.print("Enter second number");
      b=scanner.nextDouble();
      
       System.out.print("Enter an operator (+, -,*, /):");
       char operator=scannr.next().charAt(0);
       scanner.close();
       double output;
       
       switch(operator)
       {
        case '+';
        output=a+b;
        break;
        
        case '-';
        output=a-b;
        break;
        
        case '*';
        output=a*b;
        break;
        
        case '/';
        output=a/b;
        break;
        
        default:
        System.out.print("You have entered wrong number:");
        return;
        }
        }
        }
        
        
    
    

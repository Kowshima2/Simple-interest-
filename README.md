# Simple-interest-
import java.util.Scanner;

public class SimpleInterest {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in)
        System.out.print("Enter the principal amount (P): ");
        double principal = scanner.nextDouble();
        
        System.out.print("Enter the rate of interest (R) in percentage: ");
        double rate = scanner.nextDouble();
        
        System.out.print("Enter the time (T) in years: ");
        double time = scanner.nextDouble();
        
       
        double simpleInterest = (principal * rate * time) / 100;
        
        
        System.out.println("The Simple Interest is: " + simpleInterest);
        
        
        scanner.close();
    }
}

Output 
Enter the principal amount (P): 1000
Enter the rate of interest (R) in percentage: 5
Enter the time (T) in years: 2
The Simple Interest is: 100.0

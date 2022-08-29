import java.util.*;

public class SimpleInterest {
    public static void main(String[] args) {
        try {
            System.out.println("Enter the age");
            Scanner obj=new Scanner(System.in);
            int age=obj.nextInt();
            if(age>0){
            System.out.println("Enter the Principal :");
            int principle=obj.nextInt();
            System.out.println("Enter the no of Years :");
            int n=obj.nextInt();
            interest(age,principle,n);
            obj.close();
            }
            else{
                System.out.println("Invalid Age.....");
            }
            } catch (InputMismatchException e) {
                System.out.println("Invalid input");
            }
        
    }
    public static void interest(int age,int principle,int n) {
        if(age>58)  
            {
                float sim=principle*n*12/100;
                float total=principle+sim;
                System.out.println("Principle Amout : "+principle);
                System.out.println("Total Amount : "+total);
                System.out.println("Interest : "+sim);
            }
            else if(age<58 && age>0)
            {
                float sim=principle*n*10/100;
                float total=principle+sim;
           

     

                System.out.println("Invalid Age .....!");
            }
        
    }
}

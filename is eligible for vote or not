import java.util.Scanner;
import java.util.InputMismatchException;

public class eligible_vote {
    public static void main(String[] args) {
        Scanner obj = new Scanner(System.in);

        try {
            System.out.println("Enter Your Age :");
            int Age = obj.nextInt();
            if (Age >= 18) {
                System.out.println("You are Eligible to vote.....");
            } else {
                int age = 18 - Age;
                System.out.println("You are allowed to vote after : " + age + " Year");
            }
        } catch (InputMismatchException e) {
            System.out.println("Invalid Input..");
        }
    }

}

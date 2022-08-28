import java.util.Scanner;
import java.util.InputMismatchException;

public class DecimalToBinary {
    public static void toBinary(int decimal) {
        int binary[] = new int[40];
        int index = 0;
        while (decimal > 0) {
            binary[index] = decimal % 2;
            decimal = decimal / 2;
            index += 1;
        }
        for (int i = index - 1; i >= 0; i--) {
            System.out.print(binary[i]);
        }
        System.out.println();// new line
    }

    public static void toOctal(int decimal) {
        int Octal[] = new int[40];
        int index = 0;
        while (decimal > 0) {
            Octal[index] = decimal % 8;
            decimal = decimal / 8;
            index += 1;
        }
        for (int i = index - 1; i >= 0; i--) {
            System.out.print(Octal[i]);
        }
        System.out.println();// new line
    }

    public static void main(String args[]) {
        Scanner obj = new Scanner(System.in);
        try {
            System.out.println("Enter the decimal value :");
            int n = obj.nextInt();
            if(n>0){
            System.out.println("Decimal of " + n + " is: ");
            toBinary(n);
            System.out.println("Octal of " + n + " is: ");
            toOctal(n);}
            else{
                System.out.println("Invalid Input...");
            }
        } catch (InputMismatchException e) {
            System.out.println("Invalid Input..");
        }
        

    }
}

import java.util.Scanner;

public class pattern1 {
    public static void main(String[] args) {
        System.out.println("Enter the no of Lines :");
        Scanner obj = new Scanner(System.in);
        int no = obj.nextInt();
        int spaces  =no;
        int number = 1;
        for (int i = 0; i < no; i++) {
            for (int s = 1; s <= spaces; s++) {
                System.out.print(" ");
            }
            number = 1;
            for (int j = 0; j <= i; j++) {
                System.out.print(number + " ");
                number = number * (i - j) / (j + 1);
            }
            spaces--;
            System.out.println();
        }
    }

}

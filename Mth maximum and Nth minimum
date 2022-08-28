import java.util.Scanner;
import java.util.Arrays;

public class maxmin {
    public static void main(String[] args) {
        Scanner obj = new Scanner(System.in);
        int o = obj.nextInt();
        int[] arr = new int[o];
        for (int i = 0; i < arr.length; i++) {
            System.out.print("Enter the value" + i + ":");
            arr[i] = obj.nextInt();
        }
        Arrays.sort(arr);
        int m, n;
        System.out.println("Enter the M value :");
        m = obj.nextInt();
        System.out.println("Enter the N value :");
        n = obj.nextInt();
        if (m < o && m > 0 && n < o && n > 0) {
            System.out.println(m + "th Max :" + arr[o - m]);
            System.out.println(n + "th Min :" + arr[n - 1]);
            int sum=(arr[o - m])+(arr[n - 1]);  
            System.out.println("Sum :" + sum);
            System.out.println("Difference :" + (arr[o - m] - arr[n - 1]));
        } else {
            System.out.println("Invalid Input...");
        }

        obj.close();
    }
}

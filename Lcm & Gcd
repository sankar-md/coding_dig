import java.util.*;

public class lcm {
    public int gcd(int a, int b) {
        if (a > b) {
            int m = a;
        } else {
            int m = b;
        }
        int c = 0;
        for (int i = 1; i <= b; i++) {
            if (a % i == 0 && b % i == 0) {
                if (c < i) {
                    c = i;
                }
            }
        }
        return c;
    }

    public static void main(String args[]) {
        int[] a;
        a = new int[10];
        lcm obj = new lcm();
        System.out.print("enter the no of elements : ");
        Scanner ss = new Scanner(System.in);
        int n = ss.nextInt();
        if (n > 0) {
            for (int i = 0; i < n; i++) {
                System.out.print("enter the num " + i + " : ");
                a[i] = ss.nextInt();
            }
            int l = a[0];
            int g = a[0];
            for (int i = 1; i < n; i++) {
                g = obj.gcd(g, a[i]);
                l = (l * a[i]) / g;
            }
            System.out.println("gcd of " + n + " numbers : " + g);
            System.out.println("lcm of " + n + " numbers : " + l);
        } else {
            System.out.println("Invalid input...");
        }
    }
}

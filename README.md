# Sherlock-and-Moving-Tiles-Hackerrank
import java.util.*;
public class Psolving {
    public static void main(String[] args) {
        Scanner in = new Scanner (System.in);
        long L = in.nextLong();
        long S1 = in.nextLong();
        long S2 = in.nextLong();
        int Q = in.nextInt();
        for (int i = 0; i < Q; i++) {
            double q = in.nextDouble();
            q = Math.sqrt(q);
            System.out.println(Math.sqrt(2 * (L - q) * (L - q)) / Math.abs(S1 - S2));
        }
    }
}

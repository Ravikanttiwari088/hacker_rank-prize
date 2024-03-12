# hacker_rank-prize
today i got solving question prize from hacker rank
import java.util.Scanner;

public class Solution {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("================================");

        // Read inputs and print formatted output
        while (scanner.hasNext()) {
            String s = scanner.next();
            int x = scanner.nextInt();
            // Use printf to format the output
            System.out.printf("%-15s%03d%n", s, x);
        }

        System.out.println("================================");

        scanner.close();
    }
}


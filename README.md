import java.util.Scanner;

public class SumOfFiveIntegers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int sum = 0;

        System.out.println("Enter five integers:");

        for (int i = 1; i <= 5; i++) {
            System.out.print("Number " + i + ": ");
            int number = scanner.nextInt();
            sum += number;
        }

        System.out.println("The sum is: " + sum);
    }
}

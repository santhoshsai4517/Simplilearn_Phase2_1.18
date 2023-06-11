import java.util.Scanner;

public class ArithmeticCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Arithmetic Calculator");
        System.out.println("---------------------");
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();

        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        System.out.println("Select an operation:");
        System.out.println("1. Addition (+)");
        System.out.println("2. Subtraction (-)");
        System.out.println("3. Multiplication (*)");
        System.out.println("4. Division (/)");
        System.out.print("Enter your choice (1-4): ");
        int choice = scanner.nextInt();

        double result;
        boolean isValidOperation = true;

        switch (choice) {
            case 1:
                result = num1+num2;
                break;
            case 2:
                result = num1-num2;
                break;
            case 3:
                result = num1*num2;
                break;
            case 4:
                result = num1/num2;
                break;
            default:
                System.out.println("Invalid choice!");
                isValidOperation = false;
                result = 0;
        }

        if (isValidOperation) {
            System.out.println("Result: " + result);
        }

        scanner.close();
    }
}
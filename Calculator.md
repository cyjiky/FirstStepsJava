# 👾 Project 1
## ✔️ Calculator 

'''java
import java.util.Scanner;

public class Calculator {
    public static void main(String[] args) {

        Scanner scan = new Scanner(System.in);

        System.out.print("x: ");
        int a = scan.nextInt();

        System.out.print("y: ");
        int b = scan.nextInt();

        System.out.print("Welhe aufgabe ( +, -, *, / ) ?  ");
        String aufgabe = scan.next();

        int result = 0;

        switch (aufgabe) {
        case "+":
            result = a + b;
            break;

        case "-":
            result = a - b;
            break;

        case "*":
            result = a * b;
            break;

        case "/":
            if (b != 0) {
                result = a / b;
            } else {
                System.out.println("Error");
                return;
            }
            break;
        default:
            System.out.println("Error");
            return;
        }

        System.out.println("Antwort: " + result);

    }
}
'''

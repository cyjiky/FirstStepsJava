# 👾 Project 2
## ✔️ ToDoList

```java
import java.util.Scanner;

public class ToDoList {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);

        System.out.print("Was ist die erste Aufgabe? ");
        String erste = scan.next();

        System.out.print("Was ist die zweite Aufgabe? ");
        String zweite = scan.next();

        System.out.print("Was ist die dritte Aufgabe? ");
        String dritte = scan.next();

        System.out.println("Deine Aufgaben: ");
        System.out.println("1. " + erste);
        System.out.println("2. " + zweite);
        System.out.println("3. " + dritte);
    }
}
```

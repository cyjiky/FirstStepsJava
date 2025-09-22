# 👾 Project 3
## ✔️ Multiplikationstabelle 

```java
import java.util.Scanner;

public class Multiplikationstabelle {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.print("Welche Zahl? ");
        int a = scan.nextInt();
        int i = 0;

        for (i = 0; i <= 9; i++) {
            if (a > 0) {
                int result = a * i;
                System.out.println(a + " * " + i + " = " + result);
            } else {
                System.out.println("Fehler: Die Zahl muss größer als 0 sein");
            }
        }
        scan.close();
    }
}
```

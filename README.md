# HarmonicSeries

Bir harmonik serideki toplamı bulmak için:
```
import java.util.Scanner;

public class HarmonicSeries {
    public static void main(String[] args) {

        double result = 0.0;
        Scanner input = new Scanner(System.in);

        System.out.print("Bir sayı giriniz: ");
        int n =input.nextInt();

        for (double i = 1; i <= n; i++) {

            result += (1 / i);

        }
        System.out.println(result);
    }
}
```
[Patika.dev](https://app.patika.dev/iremr)

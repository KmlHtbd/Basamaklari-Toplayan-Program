# Basamaklari-Toplayan-Program
---
Bu bir [patika.dev](www.patika.dev) projesidir.
```
import java.util.Scanner;
public class basamakToplayan {
    public static void main(String[] args) {

        int a,result=0,stepValue;

        Scanner input =new Scanner(System.in);
        System.out.println("Bir sayı giriniz:");
        a = input.nextInt();

        while (a != 0){
            stepValue = a%10;
            result += stepValue;
            System.out.println(stepValue);
            a /= 10;
        }
    }
}
```

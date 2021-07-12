# Luas-Segitiga
package LuasSegitiga;
import java.util.Scanner;
public class LuasSegitiga {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.println("LUAS SEGITIGA");
        double a, b, c, s, luas;
        System.out.print("Masukkan panjang sisi pertama (a): ");
        a = scan.nextDouble();
        System.out.print("Masukkan panjang sisi kedua (b): ");
        b = scan.nextDouble();
        System.out.print("Masukkan panjang sisi ketiga (c): ");
        c = scan.nextDouble();
        s = 0.5*(a + b + c);
        luas = Math.sqrt(s*(s-a)*(s-b)*(s-c));
       System.out.println("Luas segitiga adalah "+luas);       
    } 
}

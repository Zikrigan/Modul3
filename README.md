projek saya berisi menghitung luas dan keliling dimana saya menggunakan beberapa fitur yang ada pada IJ
import java.util.Scanner;


public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Masukkan panjang persegi panjang: ");
        double panjang = input.nextDouble();

        System.out.print("Masukkan lebar persegi panjang: ");
        double lebar = input.nextDouble();

        double luas = panjang * lebar;
        double keliling = 2 * (panjang + lebar);

        /**
         * Menghitung luas persegi panjang
         */
        System.out.println("Luas persegi panjang: " + luas);
        /**
         * Menghitung keliling persegi panjang
         */
        System.out.println("Keliling persegi panjang: " + keliling);
    }
}

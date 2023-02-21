# Dairenin-Alan-n-ve-evresini-Hesaplayan-Program
www.patika.dev
------------------------------------------------


import java.util.Scanner;

public class DaireAlanCevre {
	
	public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        final double PI = 3.14;

        System.out.print("Daire diliminin yarıçapını giriniz: ");
        double r = scanner.nextDouble();

        System.out.print("Daire diliminin merkez açısının ölçüsünü giriniz: ");
        double alfa = scanner.nextDouble();

        double alan = (PI * (r * r) * alfa) / 360.0;

        System.out.println("Daire diliminin alanı: " + alan);
    }
}

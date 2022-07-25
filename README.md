// # SinifGecme.java
import System.out.println;

import java.util.Scanner;

public class SinifGecme {
    public static void main(String[] args) {
        int mat, fiz, kimya, tarih, turkce, muzik;
        Scanner inp = new Scanner(System.in);
        System.out.println(" Matematik Notunuz Giriniz : ");
        mat = inp.nextInt();
        System.out.println(" Fizik Notunuz Giriniz : ");
        fiz = inp.nextInt();
        System.out.println(" Kimya Notunuz Giriniz : ");
        kimya = inp.nextInt();
        System.out.println(" Tarih Notunuz Giriniz : ");
        tarih = inp.nextInt();
        System.out.println(" Turkce Notunuz Giriniz : ");
        turkce = inp.nextInt();
        System.out.println(" Muzik Notunuz Giriniz : ");
        muzik = inp.nextInt();

        int toplam = (mat + fiz + kimya + tarih + turkce + muzik);

        double ortalama = (toplam / 6 );

        System.out.println("not ortalamaniz " + ortalama);
    }
}

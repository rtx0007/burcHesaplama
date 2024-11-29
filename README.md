# burcHesaplama
package Exercise;

import java.util.Scanner;

public class burcBulma {
    public static void main(String[] args) {
        String month;
        int day;
        Scanner input = new Scanner(System.in);

        System.out.print("Doğduğunuz ay: ");
        month = input.nextLine().toLowerCase(); // Girilen ayı küçük harfe çeviriyoruz//       System.out.println("Doğduğunuz gün: ");
        System.out.print("Doğduğunuz gün: ");
        day = input.nextInt();

        if (month.equals("ocak")) {
            if (day <= 21) {
                System.out.println("Burcunuz: OĞLAK");
            } else {
                System.out.println("Burcunuz: KOVA");
            }
        } else if (month.equals("şubat")) {
            if (day <= 19) {
                System.out.println("Burcunuz: KOVA");
            } else {
                System.out.println("Burcunuz: BALIK");
            }
        } else if (month.equals("mart")) {
            if (day <= 20) {
                System.out.println("Burcunuz: BALIK");
            } else {
                System.out.println("Burcunuz: KOÇ");
            }
        } else if (month.equals("nisan")) {
            if (day <= 20) {
                System.out.println("Burcunuz: KOÇ");
            } else {
                System.out.println("Burcunuz: BOĞA");
            }
        } else if (month.equals("mayıs")) {
            if (day <= 21) {
                System.out.println("Burcunuz: BOĞA");
            } else {
                System.out.println("Burcunuz: İkizler");
            }
        } else if (month.equals("haziran")) {
            if (day <= 22) {
                System.out.println("Burcunuz: İkizler");
            } else {
                System.out.println("Burcunuz: Yengeç");
            }
        } else if (month.equals("temmuz")) {
            if (day <= 22) {
                System.out.println("Burcunuz: Yengeç");
            } else {
                System.out.println("Burcunuz: Aslan");
            }
        } else if (month.equals("ağustos")) {
            if (day <= 23) {
                System.out.println("Burcunuz: Aslan");
            } else {
                System.out.println("Burcunuz: Başak");
            }
        } else if (month.equals("eylül")) {
            if (day <= 23) {
                System.out.println("Burcunuz: Başak");
            } else {
                System.out.println("Burcunuz: Terazi");
            }
        } else if (month.equals("ekim")) {
            if (day <= 22) {
                System.out.println("Burcunuz: Terazi");
            } else {
                System.out.println("Burcunuz: Akrep");
                System.out.println("Wuhuu bende akrep'im");
            }
        } else if (month.equals("kasım")) {
            if (day <= 21) {
                System.out.println("Burcunuz: Akrep");
            } else {
                System.out.println("Burcunuz: Yay");
            }
        } else if (month.equals("aralık")) {
            if (day <= 21) {
                System.out.println("Burcunuz: Yay");
            } else {
                System.out.println("Burcunuz: Oğlak");
            }
        }


    }
}

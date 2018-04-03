# Coding-Game-Logika

package TugasAI;

import java.util.Scanner;

public class AI {

    public static void main(String[] args) {
        
    int perjalanan1, perjalanan2, perjalanan3, perjalanan4, perjalanan5, perjalanan6, perjalanan7;
    Scanner input = new Scanner(System.in);
    System.out.println("1.Kambing Menyebrang ");
    System.out.println("2.Serigala Menyebrang ");
    System.out.println("3.Sayuran Menyebrang ");
    System.out.println("4.Kambing Kembali ");
    System.out.println("5.Serigala Kembali ");
    System.out.println("6.Sayuran Kembali ");
    System.out.println("7.Perahu Kembali");
    System.out.println("_____________________________________________________");
    System.out.print("Perjalanan 1 :");
    perjalanan1 = input.nextInt();

    if (perjalanan1 == 1) {
        System.out.print("Perjalanan 2 :");
        perjalanan2 = input.nextInt();
    if (perjalanan2 == 7) {
        System.out.print("Perjalanan 3 :");
        perjalanan3 = input.nextInt();
    if (perjalanan3 == 2) {
        System.out.print("Perjalanan 4 :");
        perjalanan4 = input.nextInt();
    if (perjalanan4 == 4) {
        System.out.print("Perjalanan 5 :");
        perjalanan5 = input.nextInt();
    if (perjalanan5 == 3) {
        System.out.print("Perjalanan 6 :");
        perjalanan6 = input.nextInt();
                        
    if (perjalanan6 == 7) {
        System.out.print("Perjalanan 7 :");
        perjalanan7 = input.nextInt();
    if (perjalanan7 == 1) {
        System.out.println("SELAMAT!!! PERJALANAN YANG ANDA PILIH BENAR");
	System.out.println("1-7-2-4-3-7-1");
    } else {
        System.out.println("_____________________________________________________");
        System.out.println("MAAF COBA LAGI");
            }
    } else {
        System.out.println("_____________________________________________________");
        System.out.println("MAAF COBA LAGI");
            }
    } else {
        System.out.println("_____________________________________________________");
        System.out.println("MAAF COBA LAGI");
             }
    } else {
        System.out.println("_____________________________________________________");
        System.out.println("MAAF COBA LAGI");
             }
    } else {
        System.out.println("_____________________________________________________");
        System.out.println("MAAF COBA LAGI");
            }
    } else {
        System.out.println("_____________________________________________________");
        System.out.println("MAAF COBA LAGI");
        }
    } else {
        System.out.println("_____________________________________________________");
        System.out.println("MAAF COBA LAGI");
    }
}

}
    

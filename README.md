# java-4ve5inkuvvetleri
java-4ve5inkuvvetleri

import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        int n;

        Scanner input = new Scanner(System.in);
        System.out.print("Sayı giriniz : ");
        n = input.nextInt();

        for (int fo = 1, fi = 1; fo <= n && fi <= n; fo *= 4, fi *= 5) {
            System.out.println(fo + "  " + fi);
            }
        }
    }

# Manav-Kasa-Program-
Java ile kullanıcıların manavdan almış oldukları ürünlerin kilogram değerlerine göre toplam tutarını ekrana yazdıran programı yazın.

     import java.util.Scanner;

     public class Main {
     public static void main(String[] args) {

      double Armut=2.14 , Elma=3.67,   Domates=1.11 , Muz=0.95 , Patlıcan=5.00;
      Scanner gir =new Scanner(System.in);

      int  Armutkg, Elmakg, Domateskg, Muzkg, Patlıcankg;

      Armutkg=0;
      System.out.println("Armut Kaç kg :" +Armutkg);
      Elmakg=1;
      System.out.println("Elma Kaç kg :" + Elmakg);
      Domateskg=1;
      System.out.println("Domastes Kaç kg :" + Domateskg);
      Muzkg=2;
      System.out.println("Muz Kaç kg :" + Muzkg);
      Patlıcankg=3;
      System.out.println("Patlıcan Kaç kg :" +Patlıcankg);

      double Toplamtutar=(Armutkg*Armut)+(Elmakg*Elma)+(Domates*Domateskg)+(Muz*Muzkg)+(Patlıcan*Patlıcankg);
        System.out.println("Toplam Tutar :" + Toplamtutar);


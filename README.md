# CiftveDordunKatiOlanSayilar

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        int num, total=0;
        Scanner input = new Scanner(System.in);

         do{
             System.out.print("Bir sayi giriniz: ");
             num = input.nextInt();

             if(num%4==0){
                 total = total+num;
                 System.out.println(total);
             }
         }
         while (num%2==0);
             System.out.println(total);

    }
}

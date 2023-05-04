# -sHesap
import java.util.Scanner;


public class uslusayilar {
    static  int ust(int n1,int n2) {
        int sonuc = 1;
        int sonuc1=1;
        if (n2!=0){
            for (int i = 1; i <= n1; i++) {
                sonuc *= n2;
            }
            return sonuc;
        }else {
            return sonuc1;
        }
    }
    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        // kullanicidan veri alma
        System.out.print("KULLANICIDAN ALINAN ALT DEGER:");
        int n1=input.nextInt();
        System.out.print("KULLANICIDAN ALINAN UST DEGER:");
        int n2=input.nextInt();

        System.out.println("SAYILARIN KATI:"+  ust( n1,n2));
    }
}

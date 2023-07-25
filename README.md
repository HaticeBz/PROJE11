import java.util.Scanner;
public class Main {
        public static void main(String[] args){
                Scanner inp = new Scanner(System.in);
                double boy, kilo, indeks;
                System.out.print("Boyunuzu giriniz :");
                boy = inp.nextDouble();
                System.out.print("Kilonuzu giriniz :");
                kilo = inp.nextDouble();
                indeks = kilo / (boy * boy) ;
                System.out.print("Vücut kitle indeksiniz :" + indeks);
        }
}

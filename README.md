import java.util.Scanner;
public class kdv {
    public static void main(String[] args) {
Scanner input = new Scanner(System.in);
double  tutar,kdvoran = 0.18,Kdvtutar, Kdvlitutarı;
System.out.print("lütfen tutarı giriniz : " );



tutar = input.nextDouble();
        Kdvtutar = tutar * kdvoran;
        Kdvlitutarı = tutar + Kdvtutar;
System.out.println("Girdiginiz tutar : " + tutar);
System.out.println("kdv oranı : "+ 0.18);
System.out.println("Kdv tutarı :" + Kdvtutar);
System.out.println("Kdvli Tutar  :"+ Kdvlitutarı);


    }
}

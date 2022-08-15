import java.util.Scanner;

public class CokluDersCalisma {
    
public static void main(String[] args) {

Scanner bar = new Scanner(System.in);

String kullaniciadi, sifre, yenisifre, sec;

System.out.print("Kullanici Adi :");

kullaniciadi = bar.nextLine();

System.out.print("Sifre :");
        
sifre = bar.nextLine();

    if ((kullaniciadi.equals("Patika") && sifre.equals("Github5545"))) {
    System.out.print("Giris Yapıldı");
    } 
    else {
            
            System.out.println("Sifreyi Hatali Girdiniz,tekrar sıfırlamak ister misiniz :");
        }
            
            System.out.println("1-Evet\n2-Hayir");
        
        System.out.print("Sec :");
        
        sec = bar.nextLine();
        
    if (sec.equals("Hayir") || sec.equals("hayir") || 
    sec.equals("Hayır") || sec.equals("hayır")) {
            
            System.out.println("Giris Sonlandirildi");
        } 
        else if (sec.equals("Evet") || sec.equals("evet")) {
            
            System.out.print("Yeni Sifreyi Girin :");
           
    yenisifre = bar.nextLine();

    if (yenisifre.equals("Github") || yenisifre.equals("Github5545")) {
               
        System.out.println("Hatali Giris Yapildi");
                
        System.out.println("Oturumunuz Sona Ermistir");
    } 
    else {
        System.out.println("Sifre Basariyla Olusturuldu");
        }
    }
    }


    }   
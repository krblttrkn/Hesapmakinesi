# HESAP MAKİNESİ
### ÖDEV :
- Videodaki hesap makinesini **switch-case** kullanarak yapınız.

```
import java.util.Scanner;

public class switchHesap {
    public static void main(String[] args) {

        int n1 , n2 , select ;
        Scanner vote = new Scanner(System.in);
        System.out.println("-----HESAP MAKİNESİ-----");
        System.out.print("İlk Değeri Giriniz : ");
        n1 = vote.nextInt();
        System.out.print("İkinci Değeri Giriniz : ");
        n2 = vote.nextInt();
        System.out.print("1-Toplama İşlemi :\n2-Çıkarma İşlemi :\n3-Çarpma İşlemi :\n4-Bölme İşlemi :\n");
        System.out.print("Seçiminizi Giriniz : ");
        select =vote.nextInt();
        switch (select){
            case 1:
                System.out.print("Toplam : " + (n1 + n2));
                break;
            case 2:
                System.out.print("Çıkarma : " + (n1 - n2));
                break;
            case 3:
                System.out.print("Çarpma : " + (n1 * n2));
                break;
            case 4:
                switch (n2){
                    case 0 :
                        System.out.print("Bir Sayı 0'a Bölünemez.");
                        break;
                    default:
                    System.out.print("Bölme : " + (n1 / n2));
                }
                break;
            default:
                System.out.print("Yanlış Seçim Yaptınız!! Tekrar Deneyiniz!!");
        }
    }
}
```
# Patika Linkim :
***
<a href="https://academy.patika.dev/profile">Patika Profil Sayfam</a>
***

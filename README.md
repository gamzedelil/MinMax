# MinMax

package minmax;

import java.util.Scanner;

public class main {

	    public static void main(String[] args) {
	        Scanner input = new Scanner(System.in);
	        
	        System.out.println("Lutfen 4 farkli sayi giriniz:");
	        int sayi1 = input.nextInt();
	        int sayi2 = input.nextInt();
	        int sayi3 = input.nextInt();
	        int sayi4 = input.nextInt();
	        
	        int min = sayi1;
	        int max = sayi1;
	        
	        if (sayi2 < min) {
	            min = sayi2;
	        } else if (sayi2 > max) {
	            max = sayi2;
	        }
	        
	        if (sayi3 < min) {
	            min = sayi3;
	        } else if (sayi3 > max) {
	            max = sayi3;
	        }
	        
	        if (sayi4 < min) {
	            min = sayi4;
	        } else if (sayi4 > max) {
	            max = sayi4;
	        }
	        
	        System.out.println("Minimum deger: " + min);
	        System.out.println("Maksimum deger: " + max);
	    }
	}

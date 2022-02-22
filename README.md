# JavaLibs5026211113.java
tugas alpro week 2
package JavaLibs5026211113;

import java.awt.Component;
import javax.swing.Icon;
import javax.swing.JOptionPane;

public class javaLibs5026211113 {
	public static void main(String[] args) {
		 
		  //Varible
		   String Nama, Usia, Alamat, Kesibukan, Hobi, Digit1, Digit2;
	       int IntDigit1;
	       double HitungDigit, doubleDigit;
	       
	       //Method
	        String[] options = new String[]{"Boleeh","Maaf, mungkin lain kali saja"};
	        int introInt = JOptionPane.showOptionDialog(null, "Hai aku Noval, boleh kenalan tidak?", "Hello you", 0, 2, null, options, options[0]);
	        if (introInt != 0 ){
	            JOptionPane.showMessageDialog(null, "Yah baiklah, sampai jumpa dilain kesempatan","Semoga harimu Indah",2);
	            System.exit(0);
	        };
	        Nama = (String)JOptionPane.showInputDialog((Component) null, "Namamu siapa?", "Perkenalan identitas", 3, (Icon)null, (Object[])null, "" );

	        Usia = (String)JOptionPane.showInputDialog((Component) null, "Usiamu sekarang berapa?", "Perkenalan identitas", 3, (Icon) null, (Object[]) null, "");

	        Alamat = (String)JOptionPane.showInputDialog((Component) null, "Alamat rumahmu dimana?", "Perkenalan identitas", 3, (Icon)null, (Object[])null, "" );

	        Kesibukan = (String)JOptionPane.showInputDialog((Component) null, "Saat ini kamu ada kesibukan ngga? ", "Perkenalan identitas", 3, (Icon)null, (Object[])null, "" );

	        Hobi = (String)JOptionPane.showInputDialog((Component) null, "Dikeseharianmu apa sih yang paling kamu suka lakuin?", "Perkenalan identitas", 3, (Icon)null, (Object[])null, "" );

	        Digit1 = (String)JOptionPane.showInputDialog((Component) null, "Dari 1-5 angka mana yang paling kamu suka?", "Perkenalan identitas", 3, (Icon)null, (Object[])null, "" );

	        Digit2 = (String)JOptionPane.showInputDialog((Component) null, "menurut kamu rating dari percakapan ini bernilai berapa dari 1-10?", "Perkenalan identitas", 3, (Icon)null, (Object[])null, "" );
 
	        
	       //Selesai kenalan
	        String[] options2 = new String[]{"Ok"};
	        int introInt2 = JOptionPane.showOptionDialog(null, "Salam kenal ya,sampai ketemu di lain hari,semoga harimu menyenangkan :)", "Udah gini aja", 0, 2, null, options2, options2 [0]);
        
	}
}

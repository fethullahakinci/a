import java.util.Scanner; 


public class IlkProgram {

	public static void main(String[] args) {
		
		Scanner scan = new Scanner(System.in); 
				
		String yazi;
		
		System.out.print("Adınız = ");
		yazi = scan.nextLine();
		
		System.out.print("Merhaba " + yazi + ", nasılsınız?" );
		
		int yas;
		
		System.out.println();
		System.out.print("Yaşınız = ");
		yas = scan.nextInt();
				
		int dogum = 2014 - yas;		
		System.out.print(yazi + " Bey " + dogum + " yılında doğdunuz" );
		
		
	}

	

}

# NumberClass
import java.util.Scanner;
public class NomberClass{
	public static void main(String args[]) {
		Scanner sn = new Scanner(System.in);
		System.out.println("Enter a number");
		int number = sn.nextInt();
		If (number % 100 == 0){
			System.out.println("multiple of 100");
		} else {
			System.out.println("not multiple of 100")
		}
	}
}

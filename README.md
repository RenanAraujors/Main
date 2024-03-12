# Main
package curso_programacao;

import java.io.PrintStream;
import java.util.Locale;
import java.util.Scanner;

public class Main {

	public static void main(String[] args) {

		Scanner sc = new Scanner(System.in);
		int hora;
		System.out.println("Quantas horas?");
		hora = sc.nextInt();

		if (hora < 12) {
			System.out.println("bom dia");
		} else if (hora < 18) {
			System.out.println("boa tarde");
		} else {
			System.out.println("boa noite");
		}
	}
}



package curso_programacao;

import java.io.PrintStream;
import java.util.Locale;
import java.util.Scanner;

public class Main {

	public static void main(String[] args) {

		Scanner sc = new Scanner(System.in);
		System.out.println("Impar ou Par?");
		int n1 = 0;
		n1 = sc.nextInt();
		
		if (n1 >= 0) {
			System.out.println("PAR");
			}
		else {
			if (n1 < 0)
			System.out.println("IMPAR");
			else {
				System.out.println("PAR");
			}
			}
		}
	}

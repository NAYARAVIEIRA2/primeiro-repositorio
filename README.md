# primeiro-repositorio

import java.util.Scanner;

public class SenhaDeAcesso {
public static void main(String[] args) {
	
	int codigo;
	int senha;
	
	Scanner sc = new Scanner (System.in);
	System.out.println("Insira o codigo de acesso : ");
	codigo = sc.nextInt();
	if (codigo == 1234) {
		System.out.println("Insira a senha de acesso: ");
		senha = sc.nextInt();
		if ( senha == 9999) {
			System.out.println("ACESSO PERMITIDO!");
		}else {
			System.out.println("SENHA ERRADA!");
		} 
			
		}else {
			System.out.println("ACESSO INVALIDO!");
	}
	
}
}

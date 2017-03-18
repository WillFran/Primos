# Primos
import java.util.Scanner;

public class Primos {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner scan = new Scanner(System.in);
				
        int numero, elemesmo = 0,resto,contador = 0;
        System.out.println("Digite o Número:");
        numero = scan.nextInt();
        
        while(numero>= elemesmo){
        	++elemesmo;
        	resto = numero % elemesmo;
        if (resto == 0) {contador++;
            }
        } 
        if (contador <= 2){
        	System.out.println("O Número "+numero+" É Primo");
        }
        
        else {System.out.println("Número "+numero+" Não é Primo");
             }
		
		}    
	
}

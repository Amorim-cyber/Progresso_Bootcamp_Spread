<h1>Nome e Idade</h1>



Faça um programa que leia dois valores (nome e idade) repetindo n vezes e crie uma condição que finalize o loop




```java
import java.util.Scanner;

public class NomeIdade {
	public static void main(String[] args){
		Scanner scan = new Scanner(System.in);
	
		String nome;
		int idade;
		while (true){
            System.out.println("Nome:");
            nome = scan.next();
            if(nome.equals("0") break;
            System.out.println("Idade:");
            idade = scan.nextInt();	
		}
	
		System.out.println("Continua por aqui...");

		scan.close();

	}
}
```


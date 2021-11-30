<h1>Fatorial</h1>



Faça um programa que calcule o fatorial de um número inteiro fornecido pelo usuário




```java
import java.util.Scanner

public class Fatorial{
	public static void main(String[] args){
		Scanner scan = new Scanner(System.in);System.out.print("Fatorial: ");
		int fatorial = scan.nextInt();

		int multiplicacao = 1;		

		System.out.print(fatorial+"! = ");
		for(int i = fatorial;i>=1;i--){
		
			multiplicacao*=i;
		}

		System.out.println(multiplicacao);		

		scan.close();
	}
}
```


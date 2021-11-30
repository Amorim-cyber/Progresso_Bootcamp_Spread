<h1>Maior e Média</h1>



Faça um programa que leia 5 números e informe o maior número e a média desses números



```java
import java.util.Scanner;

public class MaiorMedia{
	public static void main(String[] args){
        Scanner scan = new Scanner(System.in);
        int numero;
        int count = 0;
        int maior = 0;
        int soma = 0;

        do{
            System.out.println("Numero: ");
            numero = scan.nextInt();
            soma+=numero;
            if(numero > maior) maior = numero;			

            count++;
        }while(count<5);

        System.out.println("Maior: " + maior);
        System.out.println("Média: " + soma/5);
        scan.close();
    }
}

```


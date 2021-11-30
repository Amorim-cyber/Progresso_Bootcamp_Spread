<h1>Par Impar</h1>



Faça um programa que peça n números inteiros e mostre a quantidade de números pares e a quantidade de números impares



```java
import java.util.Scanner;

public class Parimpar{
	public static void main(String[] args){
        Scanner scan = new Scanner(System.in);
        int quantNumeros;
        int numero;
        int quantPares = 0;
        int quantImpares = 0;

        System.out.println("Quantidade de números: ");
        quantNumeros = scan.nextInt();

        int count = 0;
        do{

            System.out.println("Número: ");
            numero = scan.nextInt();
            if(numero % 2 !=0) quantImpares++;
            else quantPares++;
            count++;
        }while(count < quantNumeros);

        System.out.println("Quantidade Par: " + quantPares);
        System.out.println("Quantidade Impar: " + quantImpares);
        scan.close();

    }
}

```


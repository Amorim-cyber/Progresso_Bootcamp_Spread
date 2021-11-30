<h1>Nota</h1>



Faça um programa que peça uma nota entre 0 a 10 e mostre uma mensagem caso o valor seja inválido e continue até que informe o valor certo



```java
import java.util.Scanner

public class Nota{
	public static void main(String[] args){

        Scanner scan = new Scanner(System.in);

        int nota;

        System.out.println("Nota: ");
        nota = scan.nextInt();

        while(nota < 0 | nota > 10){
            System.out.println("Nota Inválida! Digite novamente: ");
            nota = scan.nextInt();
        }

        scan.close();

    }
}


```



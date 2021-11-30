<h1>Consoantes</h1>



Faça um programa que leia um vetor de 6 caracteres, e diga quantas consoantes foram lidas e imprima as consoantes.



```java
import java.util.Scanner;

public class Consoantes{
	public static void main(String[] args){

        Scanner scan = new Scanner(System.in);

        String[] consoantes = new String[6];

        int quantidadeConsoantes = 0;

        int  count = 0;
        do{

            System.out.println("Letra: ");

            String letra = scan.next();

            if(!(letra.equalsIgnoreCase() |
                letra.equalsIgnoreCase() |
                letra.equalsIgnoreCase() |
                letra.equalsIgnoreCase() |
                letra.equalsIgnoreCase()) ){
                consoante[count] = letra;
                quantidadeConsoantes++;
            }
            count++;

        }while(count < consoantes.length);

        System.out.println("Consoantes: ");	
        for(String consoante : consoantes){
            if(consoante!=null)
            System.out.print(consoante+ " ");
        }
        System.out.println("Quantidade de consoantes: " + quantidadeConsoantes);
    }
}


```


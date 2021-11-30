<h1>Aleatório</h1>



Faça um programa que leia 20 números inteiros aleatórios (entre 0 e 100) armazene-os num vetor.
Ao final mostre os números e seus sucessores.



```java
import.java.util.random;

public class Aleatorio{
    public static void main(String[] args){

        Random random = new Random();

        int[] numerosAleatorios = new int[20];

        for(int i = 0 ; i<numerosAleatorios.length;i++){

            numerosAleatorios[i] = random.nextInt(100);						

        }

        System.out.print("Numeros Aleatórios: ");
        for (int numero : numerosAleatorios){
            System.out.print(numero + " ");	
        }

        System.out.print("\nSucessores dos Numeros Aleatórios: ");
        for (int numero : numerosAleatorios){
            System.out.print((numero+1) + " ");	
        }
    }   
}

```



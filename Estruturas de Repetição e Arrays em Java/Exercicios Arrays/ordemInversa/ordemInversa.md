<h1>Ordem Inversa</h1>



Crie um vetor de 6 números inteiros e mostre-os na ordem inversa.
		

```java
public class OrdemInversa{
	public static void main(String[] args){
		int count = 0;		
		int[] vetor = {-6, -5, 15, 50, 8, 4};	
		System.out.println("Vetor: ");
        while(count < (vetor.length - 1)){
            System.out.println(vetor[count]+ " ");
            count++;
        }

        System.out.print("\nVetor Inverso: ");
        for(int i = (vetor.length - 1);i>=0;i--){
            System.out.print(vetor[i]+ " ");
        }
    }
}
```

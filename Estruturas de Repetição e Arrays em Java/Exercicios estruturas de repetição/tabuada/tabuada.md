<h1>Tabuada</h1>



Desenvolva uma tabuada com qualquer número inteiro entre 1 a 10. O usuário deve informar de qual numero ele deseja ver a tabuada




```java
import java.util.Scanner;

public class Tabuada{
	public static void main(String[] args){
        Scanner scan = new Scanner(System.in);

        System.out.println("Tabuada: ");
        int tabuada = scan.nextInt();
        System.out.println("Tabuada de "+tabuada);

        for(int i = 1; i <= 10;i++){
            System.out.println(tabuada+ " X " + i + " = " + (i*tabuada));
        }
        scan.close();
    }
}


```


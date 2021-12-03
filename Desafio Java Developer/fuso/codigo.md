<h1>Código do exercício Fuso</h1>



```java
import java.util.Scanner;

public class Fuso {
	public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int horasaida = sc.nextInt();
        int tempoviagem = sc.nextInt();
        int fuso = sc.nextInt();
        int ajuste;
        if(horasaida + tempoviagem>=24)
            ajuste = (horasaida + tempoviagem)%24 + fuso;
        else
            ajuste = horasaida + tempoviagem + fuso;

        if(ajuste<0)
            ajuste+=24;

        System.out.println(ajuste);

        sc.close();

    }
}


```


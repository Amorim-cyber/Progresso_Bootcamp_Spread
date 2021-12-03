<h1>Código exercício do trigo no tabuleiro</h1>



```java
import java.util.Scanner;

public class Tabuleiro {
	public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int n = sc.nextInt();
        String txt="";

        for(int i=0 ; i<n ; i++) {
            int x = sc.nextInt();
            long valor = (long) Math.floor(Math.pow(2,x) / 12 / 1000);
            txt+=valor+" kg\n";
        }
        System.out.println(txt);
        sc.close();

    }
}


```


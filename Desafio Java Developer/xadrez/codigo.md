<h1>Código do exercício do Xadrez</h1>



```java
import java.util.Scanner;

public class Xadrez {
	public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int L = sc.nextInt();
        int C = sc.nextInt();

        boolean parPar = (L % 2 == 0) && (C % 2 == 0);
        boolean imparPar = (L % 2 != 0) && (C % 2 == 0);
        boolean parImpar = (L % 2 == 0) && (C % 2 != 0);
        boolean imparImpar = (L % 2 != 0) && (C % 2 != 0);

        if (parPar || imparImpar)
            System.out.println(1);
        else if(imparPar || parImpar )                                           
            System.out.println(0);
        sc.close();

    }
}


```




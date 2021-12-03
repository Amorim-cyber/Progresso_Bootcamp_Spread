<h1>Código do exercício ParImpar</h1>



```java
import java.io.IOException;
import java.util.Scanner;

public class Problem {
	public static void main(String[] args) throws IOException {
        Scanner leitor = new Scanner(System.in);
        int N = leitor.nextInt();
        String txt = "";
        for (int i = 0; i < N; i++) {
            int num = leitor.nextInt();

            boolean negativo = num < 0;
            boolean positivo = num > 0;
            boolean par = num % 2 == 0;

            if(negativo) {
                if(par) txt += "EVEN NEGATIVE\n";
                else txt += "ODD NEGATIVE\n";
            }else if(positivo) {
                if(par) txt += "EVEN POSITIVE\n";
                else txt += "ODD POSITIVE\n";
            }else {
                txt+="NULL\n";
            }
        }

        System.out.println(txt);

        leitor.close();
    }
}


```


<h1>Código exercicio Dama</h1>



```java
import java.util.Scanner;

public class Dama {
	public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	
	int x1,y1,x2,y2;
	//se estiver na mesma linha ou mesma coluna ou mesma diagonal, gasta 1 movimento
	//se estiver em qualquer outra posição, a rainha gastará 2 movimentos!
	String txt ="";
    while(true){
    	x1 = sc.nextInt();
    	y1 = sc.nextInt();
    	x2 = sc.nextInt();
    	y2 = sc.nextInt();
    	
    	boolean mesmoLugar = x1==x2 && y1==y2;
    	boolean diagonal = ((x1-y1) == (x2-y2) || (x1+y1) == (x2+y2));
    	boolean reta = (x1==x2) || (y1==y2);
    	
    	if(x1 == 0 && y1 == 0 && x2 == 0 && y2 == 0) break; //condição de parada
    	if(mesmoLugar) txt+="0\n";
        else if(diagonal || reta)txt+="1\n";
        else txt+="2\n";	
    }
    System.out.println(txt);
	sc.close();

}
}


```


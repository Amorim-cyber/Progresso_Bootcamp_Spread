<h1>Loops</h1>

<h4>O que são?</h4>

`São estruturas que tem a capacidade de repetir a execução de um fluxo de codigo`

<b>Tipos:</b>

- For (conjunto fixo de dados / sei a quantidade definida)
- While (funciona enquanto existir uma condição / não sei a quantidade definida)

<h4>Como definir e utilizar?</h4>

<h4>for</h4>

```java
for(int i=0; i<10; i++){
	System.out.println("O valor de i é "+i);
}
```

<b>Início:</b> int i = 0
<b>Fim:</b> i<10
<b>Incremento:</b> i++

<b>Tipos:</b>

- for com incremento (i++) 
- for com decremento (i--)
- for each (com objetos)
- for com iterator (pouco utilizado)
- for inifinito (inicio, fim e incremento não definidos) 

<hr>

<h4>While</h4>

```java
while (tentativas <= limiteTentativas){
	// faz a pergunta do quiz
	// Atualiza a quantidade de tentativas	 
}
```



<b>Expressão booleana:</b> tentativas <= limiteTentativas

`while infinito` acontece quando a expressão booleana é apenas true

<hr>

<h4>Alternativa do while</h4>

Executa pelo menos uma fez a expressão

```java
do{
// faz a pergunta do quiz
// Atualiza a quantidade de tentativas

}while(tentativas <= limiteTentativas);
```


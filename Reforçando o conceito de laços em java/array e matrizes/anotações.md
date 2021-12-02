<h1>Arrays</h1>

<h4>O que são?</h4>

`É um tipo de dados especial, onde um conjunto de valores podem ser armazenados`

<b>Características</b>

- Sequencial (segue uma sequência)

- Finito e fixo (tamanho limitado)

- Homogêneo (aceita um único tipo)

- Indexado (apresenta índice de acesso)

  

<img src="arrays.png"></img>



<h4>Como cria-los e utiliza-los</h4>

```java
int[] idade = new int[10];

idade[0] = 27;
idade[1] = 31;
//  ....

int[] i = {10,25};
int[] k = new int[]{1,2,3}; //mais comum

int j[] = new int[3];
```



<b>Uso de arrays em for each:</b>

```java
int[] idades = new int[] {12,35,45,22,9,37,51,61};

for(int idade: idades){
	// codigos
}
```



<h4>Matrizes</h4>

`Vetores de mais de uma dimensão (uma array de arrays)`

Exemplos:

```java
long[][] m = new long[3][3];

int[][] idades = new int[][] {{12,35},{45,22}};
```


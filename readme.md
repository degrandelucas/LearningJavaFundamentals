# Projeto: Exercícios Básicos em Java

Este projeto apresenta seis exercícios introdutórios desenvolvidos em Java, abordando conceitos básicos da linguagem, como variáveis, casting, concatenação de strings, cálculos aritméticos e formatação de saída. A seguir, são apresentados os detalhes de cada exercício.

---

## Exercício 1: Média de Duas Notas

### Objetivo
Calcular a média de duas notas decimais e exibir o resultado.

### Código
```java
public class Media {
    public static void main(String[] args) {
        double nota1 = 8.9;
        double nota2 = 7.5;
        double media = (nota1 + nota2) / 2;

        System.out.println("Média: " + media);
    }
}
```

### Descrição
Duas variáveis do tipo double armazenam as notas.
A média é calculada somando as notas e dividindo por 2.
O resultado é exibido no console.

## Exercício 2: Casting de Tipos

### Objetivo

Demonstrar o uso de casting para converter um valor do tipo double para int.

### Código
```java
public class Casting {
    public static void main(String[] args) {
        double numeroDouble = 15.7;
        int numeroInteiro = (int) numeroDouble;
        System.out.println("Casting de double para int: " + numeroInteiro);
    }
}
```

### Descrição
Um valor decimal é atribuído a uma variável double.
O valor é convertido para int, truncando as casas decimais.
O resultado é exibido no console.

## Exercício 3: Concatenação de char e String

### Objetivo
Concatenar um caractere (char) e uma palavra (String) em uma única mensagem.

```java 
public class Palavras {
    public static void main(String[] args) {
        char letra = 'A';
        String palavra = "MARELO";

        String mensagem = "A letra é " + letra + " e a palavra é " + palavra;

        System.out.println(mensagem);
    }
}
```

### Descrição
O caractere char e a palavra String são atribuídos a variáveis.
Esses valores são concatenados em uma mensagem.
O resultado é exibido no console.

## Exercício 4: Cálculo de Total da Compra

### Objetivo
Calcular o valor total de uma compra com base no preço unitário e quantidade de produtos.

```java
public class Produto {
    public static void main(String[] args) {
        double precoProduto = 29.99;
        int quantidade = 3;

        double total = precoProduto * quantidade;

        String mensagem = "O valor total da compra é R$" + total;

        System.out.println(mensagem);
    }
}
```

### Descrição
O preço do produto e a quantidade são atribuídos a variáveis.
O total é calculado multiplicando o preço pela quantidade.
O valor total é exibido em uma mensagem.

## Exercício 5: Conversão de Dólares para Reais

### Objetivo
Converter um valor em dólares para reais, considerando uma taxa de câmbio fixa.

``` java
public class ConversaoDolaresReais {
    public static void main(String[] args) {
        double valorEmDolares = 100.50;
        double taxaDeConversao = 4.94;

        double valorEmReais = valorEmDolares * taxaDeConversao;

        System.out.println("O valor em reais é: " + valorEmReais);
    }
}
```

### Descrição
O valor em dólares e a taxa de conversão são definidos.
O valor em reais é calculado multiplicando os dois valores.
O resultado é exibido no console.

## Exercício 6: Cálculo de Preço com Desconto

### Objetivo
Aplicar um desconto percentual a um preço original e calcular o novo preço.

```java
public class CalculoDesconto {
    public static void main(String[] args) {
        double precoOriginal = 150.0;

        double percentualDesconto = 10.0;
        double valorDesconto = (percentualDesconto / 100.0) * precoOriginal;
        double novoPreco = precoOriginal - valorDesconto;

        System.out.println("Preço original: R$" + precoOriginal);
        System.out.println("Desconto: R$" + valorDesconto);
        System.out.println("Novo preço com desconto: R$" + novoPreco);
    }
}
```

## Descrição
O preço original e o percentual de desconto são definidos.
O valor do desconto é calculado.
O novo preço, após o desconto, é exibido junto com os detalhes do cálculo.
Tecnologias Utilizadas
Java: Linguagem de programação usada para desenvolver os exercícios.
IDE IntelliJ IDEA: Ferramenta de desenvolvimento para editar e executar os códigos.
Autor

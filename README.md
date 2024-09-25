# Desafio Controle de Fluxo - Claro - Java com Spring Boot

Este projeto foi desenvolvido como parte do **[Claro - Java com Spring Boot](https://www.dio.me/bootcamp/coding-the-future-claro-java-spring-boot)** realizado na **[Digital Innovation One](https://dio.me)**.

O desafio consiste em exercitar os conceitos de Controle de Fluxo em Java, criando um programa que recebe dois números `inteiros` como parâmetros e realiza a impressão dos números incrementados.

## Funcionalidade

O sistema recebe dois parâmetros via terminal, que representam dois números inteiros. Com esses números, o programa realiza a seguinte ação:

- Calcula a quantidade de iterações necessárias (usando um loop `for`) para imprimir cada interação.
 - Por exemplo, se os números 10 e 20 forem passados como parâmetros, o programa realizará 10 iterações para imprimir os números de 1 a 10, como: "Imprimindo o número 1", "Imprimindo o número 2" e assim por diante.

## Exceção Personalizada
Além disso, o programa trata a situação em que o *primeiro parâmetro é MAIOR que o segundo parâmetro*. Nesse caso, o programa lança uma exceção personalizada chamada `ParametrosInvalidosException` com a seguinte mensagem: *"O segundo parâmetro deve ser maior que o primeiro"*.

## Estrutura do Projeto
O projeto `Controle de Fluxo - Desafio` está estruturado da seguinte forma:

- `Contador.java`: Esta classe contém a lógica principal do programa, onde são realizados os cálculos e a impressão dos números incrementados.

- `ParametrosInvalidosException.java`: Esta classe representa a exceção customizada que é lançada quando os parâmetros são inválidos.

## Como Executar o Projeto
Para executar o projeto, siga os seguintes passos:

1. Abra um terminal.

2. Navegue até o diretório onde o projeto DesafioControleFluxo está localizado.

3. Execute o seguinte comando:

```
java Contador 
```
    Entre com o primeiro e segundo parâmetro

    Exemplo: 10 e 20

Isso executará o programa com os números 10 e 20 como parâmetros.

4. O programa imprimirá os números incrementados no console.

## Conclusão
O projeto `Controle de Fluxo - Desafio` demonstra a aplicação dos conceitos de Controle de Fluxo em Java, além de apresentar a criação de uma exceção personalizada para lidar com situações específicas. Ele foi desenvolvido como parte do **[Claro - Java com Spring Boot](https://www.dio.me/bootcamp/coding-the-future-claro-java-spring-boot)** e é uma prova do conhecimento adquirido durante o curso.
# 02 - Conceitos Fundamentais

## Variáveis

Variáveis são espaços na memória utilizados para armazenar valores que podem ser utilizados durante a execução de um programa.

Em C, uma variável precisa ter um tipo definido. Alguns tipos comuns são:

- `int` — números inteiros;
- `float` — números com casas decimais;
- `char` — caracteres;
- `double` — números decimais com maior precisão.

## Operadores

Os operadores permitem realizar operações com os valores armazenados nas variáveis.

### Operadores aritméticos

Os principais operadores aritméticos são:

- `+` — adição;
- `-` — subtração;
- `*` — multiplicação;
- `/` — divisão;
- `%` — resto da divisão.

Exemplo:

    int a = 10;
    int b = 3;
    int resultado = a + b;

Nesse exemplo, a variável `resultado` recebe o valor `13`.

## Entrada e saída de dados

A linguagem C possui funções que permitem exibir informações na tela e receber dados do usuário.

A função `printf()` é utilizada para exibir informações:

    printf("Ola, mundo!");

A função `scanf()` pode ser utilizada para receber dados:

    int idade;
    scanf("%d", &idade);

## Estruturas condicionais

As estruturas condicionais permitem que o programa tome decisões de acordo com determinadas condições.

O exemplo mais básico utiliza `if` e `else`:

    if (idade >= 18) {
        printf("Maior de idade");
    } else {
        printf("Menor de idade");
    }

## Estruturas de repetição

As estruturas de repetição permitem executar um determinado trecho de código várias vezes.

Um exemplo é o `for`:

    for (int i = 0; i < 5; i++) {
        printf("%d\n", i);
    }

Esse código executa o comando `printf()` cinco vezes.

## Vetores

Vetores permitem armazenar vários valores do mesmo tipo em uma única estrutura.

Exemplo:

    int numeros[5] = {10, 20, 30, 40, 50};

Nesse caso, o vetor possui cinco posições.

## Resumo

Neste módulo foram apresentados conceitos fundamentais para começar a programar em C: variáveis, operadores, entrada e saída de dados, estruturas condicionais, estruturas de repetição e vetores.

No próximo módulo, esses conceitos serão utilizados em exercícios práticos.
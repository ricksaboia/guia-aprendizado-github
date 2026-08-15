# Exemplo Básico em C

## Objetivo

Este exemplo demonstra como criar um programa simples em C que recebe dois números e calcula a soma entre eles.

## Código

    #include <stdio.h>

    int main() {
        int numero1;
        int numero2;
        int soma;

        printf("Digite o primeiro numero: ");
        scanf("%d", &numero1);

        printf("Digite o segundo numero: ");
        scanf("%d", &numero2);

        soma = numero1 + numero2;

        printf("A soma e: %d\n", soma);

        return 0;
    }

## Como funciona

O programa começa incluindo a biblioteca `stdio.h`, que permite utilizar funções como `printf()` e `scanf()`.

Depois, são declaradas três variáveis inteiras:

- `numero1` para armazenar o primeiro número;
- `numero2` para armazenar o segundo número;
- `soma` para armazenar o resultado.

O programa solicita os dois números ao usuário, realiza a soma e apresenta o resultado na tela.

## Conceitos utilizados

Neste exemplo foram utilizados:

- Variáveis;
- Tipo `int`;
- Entrada de dados com `scanf()`;
- Saída de dados com `printf()`;
- Operador de adição `+`;
- Função `main()`.
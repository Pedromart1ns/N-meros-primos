# N-meros-primos

# Primeiros Números Primos no Intervalo

Este programa em C permite ao usuário inserir dois números naturais e positivos, 'x' e 'y', e em seguida, lista todos os números primos dentro do intervalo fechado [x, y].

## Como usar o programa

1. Compile o código-fonte usando um compilador C, como o gcc:

```
gcc -o numeros_primos numeros_primos.c
```

2. Execute o programa compilado:

```
./numeros_primos
```

3. Siga as instruções para fornecer os valores de 'x' e 'y' quando solicitado.

4. O programa exibirá os números primos no intervalo [x, y].

## Exemplo de Uso

```
Digite o valor de x: 10
Digite o valor de y: 30
Números primos no intervalo [10, 30]: 11 13 17 19 23 29
```

## Como funciona

1. O programa solicita ao usuário que insira dois valores inteiros, 'x' e 'y', representando o intervalo fechado de números para encontrar os primos.
2. Verifica se 'x' e 'y' são números naturais maiores que zero.
3. Troca 'x' e 'y' se 'x' for maior que 'y'.
4. Itera de 'x' até 'y', verificando se cada número é primo.
5. Um número é considerado primo se não for divisível por nenhum número além de 1 e ele mesmo.
6. Se um número for primo, ele é impresso na saída padrão.

## Observações

- O programa não considera o número 1 como primo.
- Se 'x' e 'y' forem iguais, o programa verificará apenas se esse número é primo.
- Se 'x' for maior que 'y', o programa inverterá os valores para garantir que 'x' seja menor ou igual a 'y'.
- O programa assume que os valores de entrada fornecidos pelo usuário são números inteiros. Se o usuário inserir algo que não seja um número inteiro, o comportamento do programa pode ser imprevisível.

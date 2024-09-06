## Subtração de Caracteres em Assembly x86
Este repositório contém um programa simples escrito em Assembly para arquitetura x86 que realiza a subtração entre dois caracteres numéricos e exibe o resultado na tela. O objetivo principal do código é demonstrar operações básicas com caracteres numéricos, manipulação de registradores e chamadas de sistema em Assembly.

## Descrição do Programa
O programa converte dois caracteres ASCII ('5' e '1') em seus valores numéricos, realiza a subtração entre eles e exibe o resultado na tela.

## Funcionamento
1. O programa inicializa dois caracteres ASCII ('5' e '1') e os converte para seus valores numéricos correspondentes.
2. Realiza uma subtração entre esses dois números.
3. Compara os valores para decidir qual subtração realizar, dependendo de qual número é maior.
4. Exibe o texto "A subtracao eh:" seguido do resultado da subtração.

## Estrutura do Código
- section .data: Contém a mensagem que será exibida antes do resultado.
- section .bss: Reserva espaço para armazenar o resultado da subtração.
- section .text: Contém o código principal, incluindo a lógica de subtração e as chamadas de sistema para exibição do resultado.

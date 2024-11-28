# Fibonacci Sequence - Python Script

Este repositório contém um script em Python que implementa a **sequência de Fibonacci** de duas maneiras:

- **Retornar o n-ésimo número da sequência** (`fibonacci_nth`)
- **Retornar a sequência completa até o n-ésimo número** (`fibonacci_c`)

Ambas as funções fornecem soluções para diferentes necessidades ao lidar com a sequência de Fibonacci, sendo bastante úteis tanto em cálculos matemáticos como em desafios de programação.

## O que é a Sequência de Fibonacci?

A **sequência de Fibonacci** é uma sucessão de números inteiros onde cada número após os dois primeiros é a soma dos dois anteriores. A sequência começa com:
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, ...

Ou seja:
- F(0) = 0
- F(1) = 1
- F(n) = F(n-1) + F(n-2) para n > 1

### Aplicações da Sequência de Fibonacci

A sequência de Fibonacci é amplamente utilizada em diversos campos, como:
- **Matemática**: Como uma das sequências numéricas mais conhecidas, com várias propriedades matemáticas interessantes.
- **Ciência da Computação**: Utilizada em algoritmos de busca, programação dinâmica, algoritmos recursivos, e até mesmo na análise de complexidade de algoritmos.
- **Entrevistas de Emprego**: Problemas envolvendo a sequência de Fibonacci são comuns em entrevistas para desenvolvedores, pois ajudam a testar habilidades fundamentais como:
  - Compreensão de recursão
  - Eficiência de algoritmos
  - Capacidade de otimizar código
  - Solução de problemas de forma criativa

## Funções do Script

### 1. `fibonacci_nth(n)`
Esta função recebe um número `n` e retorna o n-ésimo número da sequência de Fibonacci.

#### Exemplo:

print(fibonacci_nth(9))  # Saída: 34

**Como funciona:**

A função inicializa a sequência com os dois primeiros números [0, 1].
Em seguida, calcula os próximos números da sequência de forma iterativa até alcançar o n-ésimo número.
Retorna o número de índice n na sequência.

### 2. fibonacci_c(n)
Esta função retorna a sequência completa de Fibonacci até o n-ésimo número (inclusive).
Exemplo:
print(fibonacci_c(9))  # Saída: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]

**Como funciona:**

Inicializa a sequência com [0, 1].
Calcula iterativamente cada número e o adiciona à lista fib_list.
Retorna a sequência completa até o índice n.

## Como Usar
1. Clone ou baixe o repositório em seu computador.
2. Execute o script em um ambiente Python.
3. Utilize as funções fibonacci_nth(n) ou fibonacci_c(n) com o valor desejado de n.

### Exemplo de Uso:
**Exibe o 9º número da sequência de Fibonacci**
- print(fibonacci_nth(9))

**Exibe a sequência completa até o 9º número**
- print(fibonacci_c(9))

## Por que Estudar a Sequência de Fibonacci?
Durante entrevistas técnicas de programação, perguntas sobre a sequência de Fibonacci são frequentes porque ela envolve conceitos essenciais da ciência da computação, como:

- **Recursão:** A sequência é um exemplo clássico de recursão.
- **Otimização:** Como calcular a sequência de forma eficiente, evitando cálculos redundantes (como em soluções recursivas ingênuas).
- **Algoritmos:** Como melhorar a eficiência de um algoritmo (como transformar uma solução recursiva em uma solução iterativa ou dinâmica).
Saber implementar e otimizar a sequência de Fibonacci é uma habilidade importante para qualquer programador iniciante, e este script é uma maneira simples de entender e testar esse conceito.

## Contribuições
Se você quiser contribuir com melhorias ou correções para o script, fique à vontade para abrir uma issue ou fazer um pull request!

## Licença
Este projeto é de código aberto sob a licença MIT.



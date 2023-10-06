# Calculadora React

Este é um projeto de calculadora criada utilizando a biblioteca React. A calculadora é capaz de realizar operações básicas de matemática, como adição, subtração, multiplicação e divisão. Ela também possui funcionalidades para limpar o visor.

## Tecnologias Utilizadas

- React: A biblioteca JavaScript utilizada para criar a interface de usuário da calculadora.
- Styled-components: Uma biblioteca para estilizar os componentes React.

## Funcionalidades

A calculadora possui as seguintes funcionalidades:

1. **Visor de Números**: O visor exibe os números digitados e os resultados das operações.

2. **Botões Numéricos**: Existem botões numerados de 0 a 9 que permitem inserir números no visor. Clique em um número para adicioná-lo ao visor.

3. **Botões de Operação**: Existem botões para as operações de adição (+), subtração (-), multiplicação (*) e divisão (/). Clique em um botão de operação para selecionar a operação desejada.

4. **Botão de Igual (=)**: Clique no botão "=" para calcular o resultado da operação atual.

5. **Botão de Limpar (C)**: Clique no botão "C" para limpar o visor e as operações.

6. **Cálculo Contínuo**: Após realizar uma operação, você pode continuar realizando operações com o resultado atual como o novo número inicial.

## Estrutura do Código

O código-fonte da calculadora é organizado da seguinte maneira:

- `App.js`: O componente principal que renderiza a interface da calculadora e gerencia o estado dos números e operações.

- `components/Input.js`: Um componente de entrada que exibe o número atual no visor.

- `components/Button.js`: Um componente de botão que é usado para os números, operações e ação de limpar.

## Funções Principais

- `handleOnClear()`: Limpa o visor e redefine os valores iniciais.

- `handleAddNumber(num)`: Adiciona um número ao visor.

- `handleSumNumbers()`: Realiza a adição.

- `handleMinusNumbers()`: Realiza a subtração.

- `handleMultNumbers()`: Realiza a multiplicação.

- `handleDivideNumbers()`: Realiza a divisão.

- `handleEquals()`: Calcula o resultado da operação atual.




# Variáveis

Em programação, uma variável é um local de armazenamento nomeado que contém um valor. Em JavaScript, você pode criar variáveis usando a palavra-chave `var`, `let` ou `const`.

- `var`: Era a forma antiga de declarar variáveis em JavaScript, mas com o ECMAScript 6 (ES6), surgiram `let` e `const` que são preferidos.

- `let`: Declara uma variável que pode ser reatribuída. Isso significa que você pode mudar o valor da variável posteriormente no código.

- `const`: Declara uma variável com um valor constante, ou seja, uma vez atribuído, não pode ser reatribuído. Isso é útil quando você tem valores que não devem ser alterados durante a execução do programa.

Aqui estão alguns exemplos:

```javascript
// Exemplo usando var (não recomendado)
var numero = 5;
numero = 10;  // Pode ser reatribuído

// Exemplo usando let
let idade = 25;
idade = 30;  // Pode ser reatribuído

// Exemplo usando const
const PI = 3.14;
// PI = 3.14159;  // Isso geraria um erro, pois não pode ser reatribuído
```

**Tipos de Dados:**
JavaScript é uma linguagem de tipagem dinâmica, o que significa que o tipo de uma variável pode ser alterado durante a execução do programa. Alguns tipos de dados comuns são:

- `Number`: Números inteiros ou de ponto flutuante.
- `String`: Sequência de caracteres.
- `Boolean`: Valor lógico, `true` ou `false`.
- `Array`: Uma coleção ordenada de valores.
- `Object`: Um contêiner para propriedades nomeadas.

Exemplo:

```javascript
let numero = 42;           // Number
let nome = "John";         // String
let estaChovendo = true;   // Boolean

let lista = [1, 2, 3, 4];   // Array
let pessoa = {             // Object
  nome: "Alice",
  idade: 28,
  casada: false
};
```

**Operadores:**
Operadores são símbolos que realizam operações em variáveis e valores. Alguns operadores básicos incluem:

- Aritméticos: `+` (adição), `-` (subtração), `*` (multiplicação), `/` (divisão), `%` (resto).
- Comparação: `==` (igual a), `!=` (diferente de), `>` (maior que), `<` (menor que), `>=` (maior ou igual a), `<=` (menor ou igual a).
- Lógicos: `&&` (E lógico), `||` (OU lógico), `!` (NÃO lógico).

```javascript
let a = 5;
let b = 10;

let soma = a + b;       // 15
let diferenca = a - b;  // -5
let multiplicacao = a * b;  // 50
let divisao = a / b;    // 0.5
let resto = a % b;      // 5 (resto da divisão)

let igualdade = a == b; // false
let maiorQue = a > b;   // false
let andLogico = (a > 0) && (b > 0); // true se ambos forem verdadeiros

// Existem muitos outros operadores e conceitos em JavaScript, mas esses são os básicos.
```

Espero que isso forneça uma introdução sólida ao conceito de variáveis em JavaScript. Se você tiver mais perguntas ou precisar de esclarecimentos sobre algum ponto específico, sinta-se à vontade para perguntar!
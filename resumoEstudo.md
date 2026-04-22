# 📘 Resumo Estruturado: Lógica de Programação e Linguagem C

Este resumo foi elaborado para cobrir os principais conteúdos exigidos em estudos e avaliações, abrangendo desde a **lógica teórica** até a **aplicação prática em linguagem C** e conceitos de mercado.

---

## 🧠 1. Fundamentos de Lógica e Algoritmos

### 🔹 Lógica de Programação
Técnica de organizar pensamentos e instruções de forma sequencial e coerente para resolver problemas.

📌 Importante:
- Computadores são **determinísticos**
- Não possuem intuição → exigem instruções claras e precisas

---

### 🔹 Algoritmo
Sequência finita de passos para executar uma tarefa (como uma **receita**).

**Exemplo:**
> Fazer batatas fritas → a ordem importa (não dá para fritar antes de descascar)

---

### 🔹 Método da Caixa Preta
Foco em:
- **Entrada (Input)**
- **Saída (Output)**

Sem se preocupar inicialmente com o processamento interno.

---

## 📊 2. Dados e Memória

### 🔹 Variáveis
Espaços na memória que podem ter seus valores alterados durante a execução.

### 🔹 Constantes
Valores fixos que não mudam durante o programa.

---

### 🔹 Tipos de Dados

| Tipo        | Descrição                         | Exemplo          |
|------------|----------------------------------|------------------|
| `int`      | Números inteiros                 | idade, contador  |
| `float`    | Números decimais                 | peso, altura     |
| `double`   | Maior precisão decimal           | cálculos científicos |
| `char`     | Um caractere                     | 'A', 'b'         |
| `string`   | Conjunto de caracteres           | "nome"           |
| `bool`     | Valor lógico                     | true / false     |

---

## ➗ 3. Operadores

### 🔹 Aritméticos
- `+` adição  
- `-` subtração  
- `*` multiplicação  
- `/` divisão  
- `%` resto da divisão  

---

### 🔹 Relacionais
Utilizados para comparação:

- `>` maior que  
- `<` menor que  
- `>=` maior ou igual  
- `<=` menor ou igual  
- `==` igual  
- `!=` diferente  

---

### 🔹 Lógicos

- `&&` → E (AND)  
- `||` → OU (OR)  
- `!` → NÃO (NOT)  

---

## 🔀 4. Estruturas de Controle de Fluxo

### 🔹 Condicionais

Permitem tomada de decisão:

- `if`
- `else if`
- `else`

Podem ser:
- Simples
- Compostas
- Encadeadas

---

### 🔁 Laços de Repetição

| Estrutura | Característica |
|----------|--------------|
| `for`    | Número de repetições conhecido |
| `while`  | Executa enquanto condição for verdadeira |
| `do-while` | Executa pelo menos uma vez |

---

## 💻 5. Introdução à Linguagem C

### 🔹 Sintaxe Básica

- Blocos definidos por `{ }`
- Instruções terminam com `;`
- Todo programa possui a função `main`

---

### 🔹 Entrada e Saída

- `printf` → exibe dados  
- `scanf` → lê dados do usuário  

**Exemplo:**
```c
scanf("%i", &valor);

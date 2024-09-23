# Norminette - Regras da Escola 42

A **Norminette** é o linter oficial da escola 42, responsável por garantir que o código siga uma padronização e boas práticas de programação. Abaixo estão as principais regras:

## 1. Estrutura do Arquivo

- Cada arquivo deve ter no máximo **5 funções**.
- Cada função não pode ultrapassar **25 linhas**.
- Cada linha deve ter no máximo **80 caracteres** (sem contar o `\n` no final).
- Não pode haver linhas vazias no final dos arquivos.
- O código deve ser em inglês.

## 2. Funções

- O nome das funções deve ser **autoexplicativo** e em **snake_case**.
- Funções não podem ter mais do que **4 parâmetros**.
- As funções devem ser **bem documentadas** com comentários relevantes quando necessário.

## 3. Variáveis

- Nomes de variáveis devem estar em **snake_case**.
- Evitar o uso de variáveis globais, sempre que possível.
- Todas as variáveis devem ser **inicializadas** antes de serem usadas.

## 4. Indentação e Espaços

- A indentação deve ser feita com **tabulações** (não espaços).
- Cada nível de indentação corresponde a um único **tab**.
- Não deve haver **espaços em excesso** ao final de uma linha.
- Sempre que abrir uma nova chave `{`, a indentação deve ser aumentada e reduzida quando fechar a chave `}`.

## 5. Comentários

- Comentários devem ser colocados **acima** da linha de código relevante.
- Evitar comentários desnecessários ou óbvios.
- Comentários devem ser **curtos e precisos**.

## 6. Definições

- Definições de macros (`#define`) devem estar em **letras maiúsculas** e separadas por underscore (`_`).
- Constantes definidas por `#define` devem ser preferencialmente usadas para **valores fixos**.
- **Funções não podem ser definidas** em arquivos `.h`.

## 7. Operadores e Condicionais

- Operadores devem ser cercados por **espaços** (e.g., `a + b`, e não `a+b`).
- Condicionais (`if`, `else`, `while`, etc.) devem ter parênteses bem formatados, como:
  ```c
  if (condition)
  {
      // Código
  }

# 💱 Conversor de Moedas Universal - Arquitetura e Organização de Computadores

> **Projeto Acadêmico - Universidade Tecnológica Federal do Paraná (UTFPR)**
> **Disciplina:** Arquitetura de Computadores

Este repositório contém a implementação de um **Conversor de Moedas Universal** desenvolvido em C++. O objetivo principal deste projeto não é apenas a lógica de software, mas a análise pedagógica da tradução de código de alto nível (C++) para linguagem de montagem (**Assembly**).

## 🎯 Objetivo do Projeto

No contexto da disciplina de Arquitetura de Computadores, este projeto visa:
1.  Implementar lógica de manipulação de dados e operações de ponto flutuante (`float`/`double`) em C++.
2.  Utilizar o compilador (GCC/G++) para gerar o código Assembly correspondente.
3.  Analisar como estruturas de controle (if/else, loops) e operações aritméticas são representadas nas instruções do processador (ex: `MOV`, `ADD`, `MUL`, `JMP`).

## 🛠️ Funcionalidades

* Conversão entre múltiplas moedas (Real, Dólar, Euro, Libra, Iene).
* Interface via console (CLI) para entrada de dados.
* Tabela de taxas de câmbio pré-definidas (fixas para fins de demonstração da arquitetura).
* **Arquivo de Saída Assembly:** O projeto é configurado para expor o código de máquina legível.

## 🚀 Como Compilar e Gerar o Assembly

Para realizar a análise da arquitetura, utilizamos o `g++` para interromper a compilação na etapa de tradução para Assembly.

### Pré-requisitos
* Compilador G++ (MinGW no Windows ou padrão no Linux/macOS).

### 1. Gerar o Executável (Uso normal)
Para apenas rodar o programa:
```bash
g++ main.cpp -o conversor
./conversor

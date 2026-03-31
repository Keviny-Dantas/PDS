# Estudo Dirigido - Parte 1: Modelagem de Sinais e Sistemas Discretos

Este repositório contém o desenvolvimento da primeira etapa da disciplina de **Processamento Digital de Sinais (PDS)**. O trabalho aborda a fundamentação matemática, a simulação computacional e a análise de propriedades estruturais de sinais e sistemas no domínio discreto.

## 👤 Identificação
* **Aluno:** Keviny Ryan Menezes Dantas
* **Matrícula:** 202321250020
* **Instituição:** Instituto Federal da Paraíba (IFPB)
* **Curso:** Engenharia da Computação
* **Disciplina:** Processamento Digital de Sinais
* **Professor:** Dr. Moacy Pereira da Silva

---

## 🎯 Objetivo do Estudo
O objetivo central desta etapa é responder ao **Problema Norteador**: 
> *"Como representar matematicamente o comportamento temporal de um sensor real e quais propriedades estruturais devem ser analisadas para garantir o correto processamento digital desse sinal?"*

Através de simulações em Python, exploramos a transição entre fenômenos físicos contínuos e sequências numéricas discretas, validando conceitos de amostragem, energia e classificação de sistemas.

---

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3
* **Ambiente:** Google Colaboratory
* **Bibliotecas:** * `NumPy`: Processamento numérico e manipulação de vetores.
    * `Matplotlib`: Visualização de dados e geração de gráficos de hastes (*stem plots*).

---

## 📂 Estrutura do Projeto
O estudo está dividido em três seções principais:

1.  **Geração de Sinais Básicos:** Modelagem de impulsos, degraus e exponenciais complexas (autofunções).
2.  **Operações e Energia:** Manipulação temporal (deslocamento, inversão, decimação) e caracterização de sinais de energia vs. potência.
3.  **Classificação de Sistemas:** Testes de linearidade (superposição), causalidade, estabilidade BIBO, invariância temporal e invertibilidade.

---

## 📈 Discussão Técnica e Conclusões
As simulações realizadas demonstram que:
* **Causalidade** é um requisito físico inegociável para processamento em tempo real (Sistemas Embarcados/RTL).
* **Estabilidade BIBO** é essencial para prevenir *overflow* em unidades aritméticas de ponto fixo.
* **Sistemas LIT** (Lineares e Invariantes no Tempo) são a base para o design de filtros digitais, garantindo previsibilidade e eficiência na área de silício.
* **Decimação** permite a otimização do consumo de potência em sistemas de alta performance, desde que respeitados os limites de *aliasing*.

---

## 🚀 Como Executar
1. Acesse o arquivo `.ipynb` na pasta `/simulacoes`.
2. Abra através do [Google Colab](https://colab.research.google.com/).
3. Execute as células sequencialmente para observar as respostas dos sistemas aos estímulos propostos.

---
**IFPB - Campus Campina Grande** *2026.1*

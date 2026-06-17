# 📡 Estudo Dirigido 04 – Filtros Digitais em Processamento Digital de Sinais

## 📖 Sobre o Projeto

Este repositório contém a resolução do **Estudo Dirigido 04** da disciplina de **Processamento Digital de Sinais (PDS)**, desenvolvido no curso de **Engenharia da Computação** do **Instituto Federal da Paraíba (IFPB) – Campus Campina Grande**.

As atividades propostas abordam os principais conceitos relacionados ao projeto, análise e aplicação de filtros digitais, utilizando implementações práticas em **Python** por meio do **Google Colab**.

O estudo combina os fundamentos teóricos apresentados por **Oppenheim e Schafer** com experimentos computacionais envolvendo análise nos domínios do tempo e da frequência, permitindo compreender o comportamento de sistemas de filtragem digital sob diferentes perspectivas.

---

## 🎯 Objetivos do Estudo

- Compreender os fundamentos da filtragem digital;
- Projetar filtros digitais FIR e IIR;
- Analisar respostas em frequência e em fase;
- Investigar polos, zeros e estabilidade de sistemas digitais;
- Comparar filtros FIR e IIR sob diferentes perspectivas;
- Aplicar técnicas de filtragem na remoção de ruídos e na separação espectral de sinais;
- Desenvolver habilidades práticas de implementação utilizando Python e ferramentas computacionais de análise de sinais.

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- Google Colab
- NumPy
- SciPy
- Matplotlib

---

## 📚 Conteúdos Abordados

### Questão 01 – Filtragem de um Sinal Composto por Duas Senoides
- Geração de sinais compostos;
- Projeto de filtro passa-baixa;
- Análise temporal e espectral.

### Questão 02 – Remoção de Ruído Utilizando um Filtro FIR
- Geração de ruído branco gaussiano;
- Filtragem FIR;
- Comparação entre sinais ruidosos e filtrados.

### Questão 03 – Comparação entre Filtros FIR e IIR Butterworth
- Projeto de filtros FIR e IIR;
- Aplicação em sinais contaminados por ruído;
- Comparação de desempenho.

### Questão 04 – Comparação das Respostas em Frequência
- Banda de passagem;
- Banda de rejeição;
- Seletividade espectral;
- Comparação entre filtros FIR e IIR.

### Questão 05 – Análise de Polos e Zeros de um Filtro IIR
- Plano-z;
- Estabilidade de sistemas digitais;
- Relação entre polos, zeros e resposta em frequência.

### Questão 06 – Comparação das Respostas ao Impulso
- Resposta ao impulso de filtros FIR;
- Resposta ao impulso de filtros IIR;
- Efeitos da realimentação.

### Questão 07 – Projeto de um Filtro Digital Passa-Faixa
- Geração de sinais multifrequenciais;
- Seleção de componentes espectrais;
- Análise no domínio da frequência.

### Questão 08 – Comparação das Respostas de Fase
- Resposta de fase;
- Distorção temporal;
- Preservação da forma de onda.

### Questão 09 – Análise do Atraso de Grupo
- Group Delay;
- Relação entre fase e atraso temporal;
- Preservação da estrutura temporal dos sinais.

### Questão 10 – Aplicação Integrada de Filtragem Digital
- Separação entre sinal útil e interferências;
- Recuperação de informações de interesse;
- Integração dos conceitos estudados ao longo do roteiro.

---

## 🧠 Conceitos Fundamentais Estudados

Durante o desenvolvimento deste estudo dirigido foram explorados conceitos fundamentais de Processamento Digital de Sinais, tais como:

- Sistemas Lineares Invariantes no Tempo (LIT);
- Resposta ao Impulso;
- Convolução;
- Transformada Discreta de Fourier (DFT);
- Transformada Rápida de Fourier (FFT);
- Resposta em Frequência;
- Resposta de Fase;
- Atraso de Grupo;
- Filtros FIR (*Finite Impulse Response*);
- Filtros IIR (*Infinite Impulse Response*);
- Polos e Zeros;
- Estabilidade de Sistemas Digitais;
- Filtragem Passa-Baixa;
- Filtragem Passa-Faixa;
- Remoção de Ruído e Separação Espectral.

---

## 📂 Estrutura do Repositório

```text
📦 Estudo-Dirigido-04-PDS
 ┣ 📂 Resumo Teórico
 ┃ ┗ 📄 Resumo_Teorico_Estudo_Dirigido_04.pdf
 ┣ 📂 Simulações e Resultados
 ┃ ┗ 📓 Estudo_Dirigido_04.ipynb
 ┗ 📜 README.md
```

---

## 📁 Organização do Repositório

### 📂 Resumo Teórico
Contém o documento em PDF com a fundamentação teórica utilizada no desenvolvimento do estudo dirigido, apresentando os principais conceitos de Processamento Digital de Sinais e filtros digitais abordados nas atividades propostas.

### 📂 Simulações e Resultados
Contém o notebook desenvolvido no Google Colab (`.ipynb`), reunindo todas as implementações em Python, simulações computacionais, gráficos, análises e discussões dos resultados obtidos em cada uma das dez questões.

### 📜 README.md
Arquivo responsável pela apresentação geral do projeto, contendo sua descrição, objetivos, tecnologias utilizadas, conteúdos abordados, organização dos arquivos e referências bibliográficas.

---

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/Estudo-Dirigido-04-PDS.git
```

### 2. Acesse a pasta do projeto

```bash
cd Estudo-Dirigido-04-PDS
```

### 3. Abra o notebook

O notebook encontra-se na pasta:

```text
Simulações e Resultados/
└── Estudo_Dirigido_04.ipynb
```

O projeto foi desenvolvido no **Google Colab**, podendo ser executado diretamente na plataforma ou em qualquer ambiente compatível com **Jupyter Notebook**.

---

## 📖 Referência Bibliográfica

OPPENHEIM, Alan V.; SCHAFER, Ronald W. **Discrete-Time Signal Processing**. 3. ed. Upper Saddle River: Pearson, 2010.

---

## 👨‍💻 Autor

**Keviny Ryan Menezes Dantas**  
Graduando em Engenharia da Computação  
Instituto Federal da Paraíba – IFPB Campus Campina Grande

---

## 📄 Licença

Este repositório possui finalidade exclusivamente acadêmica e educacional, sendo destinado ao estudo de técnicas de Processamento Digital de Sinais e à implementação de filtros digitais utilizando Python.
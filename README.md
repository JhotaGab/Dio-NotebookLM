# 🐍 Python Tutor: Análise Estrutural e Pedagógica (NotebookLM)

> **Projeto Educacional Baseado em IA**
> Este repositório contém a estrutura, fontes e diretrizes para configurar um assistente **NotebookLM** focado no ensino de Python, baseado na metodologia acadêmica da Universidade de São Paulo (USP) e na documentação oficial da linguagem.

## 📖 Sobre o Projeto

O objetivo deste projeto é utilizar o Google NotebookLM para criar um tutor inteligente que não apenas fornece código, mas ensina a "pensar como um cientista da computação". A base de conhecimento foi extraída da **"Análise Estrutural e Pedagógica do Ensino de Python"**, que consolida práticas de ensino de instituições de prestígio e a infraestrutura comunitária brasileira .

O modelo pedagógico foca na conversão do entusiasmo inicial do aluno em competência analítica e técnica .

## 🏗️ Pilares da Metodologia

O assistente é fundamentado em três princípios extraídos da análise técnica:

1.  **Rigor Acadêmico (USP):** Segue o currículo do curso "Introdução à Ciência da Computação com Python", coordenado pelo Prof. Fabio Kon, estruturado em módulos semanais de dedicação intensiva .
2.  **Cultura de QA (Quality Assurance):** Diferente de cursos tradicionais, este método introduz testes automatizados com `pytest` precocemente (Módulos 3-5), incentivando o TDD (Test-Driven Development) .
3.  **Feedback Instantâneo:** Simula a experiência de um "corretor automático" (*automatic grader*), permitindo ciclos rápidos de correção de falhas lógicas e sintáticas .

## 📚 Estrutura Curricular (Knowledge Base)

O NotebookLM está configurado para guiar o aluno através da seguinte progressão de competências:

| Módulo | Foco Temático | Aplicação Prática | Competências Desenvolvidas |
| :--- | :--- | :--- | :--- |
| **1 e 2** | **Fundamentação** | Instalação e Variáveis | Manipulação de tipos primitivos e configuração de ambiente . |
| **3 a 5** | **Lógica de Controle** | Condicionais e Repetição | Implementação de loops `while` e decisões lógicas . |
| **6** | **Engenharia de Software** | Depuração e Refatoração | Limpeza de código e estratégias de depuração . |
| **7 a 9** | **Estruturas Avançadas** | Listas e Objetos | Manipulação de coleções de dados e gestão de memória . |
| **Final** | **Síntese Algorítmica** | Projeto COH-PIAH | Análise estatística e detecção de similaridade textual . |

## 🎮 Projetos Desafio (Milestones)

O aprendizado é consolidado através de dois projetos principais detalhados na documentação:

### 1. Jogo do NIM 
* **Conceito:** Teoria dos jogos e algoritmos de decisão.
* **Desafio:** Implementar uma estratégia onde o computador joga de forma otimizada (impossível de ser derrotado se começar jogando).

### 2. Caso COH-PIAH 
* **Conceito:** Linguística Computacional e Ciência de Dados.
* **Desafio:** Analisar assinaturas estilométricas em textos para identificar a autoria, manipulando grandes volumes de strings.

## ⚙️ Tópicos Avançados (Under the Hood)

Para alunos que desejam ir além da sintaxe, o projeto cobre aspectos da arquitetura do CPython (versão 3.14.3) :

* **Gestão de Memória:** Explicação sobre contagem de referências e coleta de lixo cíclica para evitar *memory leaks* .
* **Extensibilidade:** Como criar módulos em C/C++ que são carregados dinamicamente pelo interpretador .
* **Otimização:** Uso de avaliação preguiçosa (*lazy evaluation*) em funções como `range()` .

## 🌐 Comunidade e Suporte

O projeto incentiva a integração com o ecossistema Python Brasil:
* **PUGs (Python User Groups):** Grupos locais para mentoria e networking .
* **Canais Digitais:** Participação em grupos de Telegram/Discord focados em áreas como Data Science e Web (Django/Flask) .

## 🚀 Como Usar este Repositório

1.  Carregue o arquivo PDF base deste repositório no seu **NotebookLM**.
2.  Utilize os prompts sugeridos na pasta `prompts/` para iniciar sessões de estudo focadas (ex: "Explicar a lógica do Jogo do NIM").
3.  Utilize o recurso de *Audio Overview* para ouvir uma discussão sobre a importância dos testes automatizados na carreira de dev.

---
*Baseado na documentação oficial do Python e nas diretrizes do Coursera/USP.*

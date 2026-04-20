# 🐍 Caderno Temático: Domine Python e Fluxos de Trabalho Agentes

![Python Version](https://img.shields.io/badge/python-3.14.4-blue.svg)
![Status](https://img.shields.io/badge/status-em_desenvolvimento-green.svg)
![Category](https://img.shields.io/badge/category-ADS_/_IA-orange.svg)

## 🎯 Contexto e Objetivos

> Este repositório é o resultado de um estudo direcionado na maestria da linguagem **Python**, integrando fundamentos clássicos com as fronteiras da **Inteligência Artificial**. 

O assunto escolhido para este caderno temático abrange desde a **Sintaxe Estruturada e POO** até a aplicação dessas bases na construção de **Agentes Inteligentes**, servindo como base técnica para o projeto **EduMentor AI**.

### 🚀 Objetivos de Estudo

* **🧱 Domínio Técnico Gradual:** Consolidar o conhecimento através dos **4 "Mundos"** (Fundamentos, Controle, Estruturas Compostas e POO).
* **🤖 Integração com IA Generativa:** Utilização do Python para explorar *Agentic Design Patterns* e a técnica **ReAct**.
* **📚 Base de Conhecimento:** Criar um guia de referência rápido que una teoria acadêmica com resoluções práticas.
* **✍️ Prompt Engineering:** Desenvolver e refinar prompts estratégicos para extrair o máximo potencial analítico de LLMs.

---

## 📚 Curadoria de Fontes (NotebookLM)

| Fonte | Descrição | Link |
| :--- | :--- | :--- |
| **Documentação Oficial** | Fonte primária de verdade sobre a linguagem (v3.14.4). | [Acessar](https://docs.python.org/3/) |
| **The Hitchhiker’s Guide** | Melhores práticas de ambiente e estruturação. | [Acessar](https://docs.python-guide.org/) |
| **Python Brasil (Wiki)** | Acervo comunitário focado em lógica e algoritmos. | [Acessar](https://wiki.python.org.br/ListaDeExercicios) |
| **Curso em Vídeo** | Base didática para progressão prática de desafios. | [Acessar](https://www.youtube.com/c/cursoemvideo) |

---

## 🧠 Engenharia de Prompts (Biblioteca de Consulta)

Abaixo estão os prompts estratégicos desenvolvidos. Clique em cada seção para expandir e copiar o conteúdo com a formatação correta.

### 📑 Prompt 1: Fundamentos e Estrutura Mental
**Objetivo:** Entender a semântica e organização de dados.
<details>
<summary>Clique para expandir o Prompt</summary>

```text
Aja como um tutor especializado em Python. 
Preciso de uma aula teórica em texto sobre os fundamentos da linguagem. 
Aborde os seguintes tópicos de forma didática:

1. Interpretador: Como o código é lido e a indentação obrigatória.
2. Variáveis e Tipagem: Dinamismo e tipos básicos (int, float, bool).
3. Strings: Declaração, f-strings e métodos (.lower, .replace).
4. Funções e Escopo: Uso de def, argumentos e variáveis locais/globais.
5. Bibliotecas: O uso do import para expansão de recursos.

Ao final, crie um único script de exemplo que utilize todos esses conceitos.
```

### 📝 Prompt 2: Roteiro de Desafios Lógicos
**Foco:** Prática progressiva e aprendizado ativo.
<details>
<summary>Clique para expandir o Prompt</summary>
    
```text
Crie um roteiro de 5 exercícios de programação em Python com dificuldade progressiva:

- Nível 1 (Básico): Exercício com print() e input().
- Nível 2 (Cálculo): Operações matemáticas e armazenamento em variáveis.
- Nível 3 (Decisão): Uso de if, elif e else para lógica de caminhos.
- Nível 4 (Repetição): Uso de while ou for para processar listas.
- Nível 5 (Projeto Funcional): Sistema de 'Controle de Pedidos' ou 'Calculadora' com funções.

Forneça apenas os enunciados. 
Diga que está aguardando eu enviar a solução do primeiro para você corrigir.
```

### 🗄️ Prompt 3: Integração com Bancos de Dados
**Foco:** Persistência de dados e infraestrutura.
<details>
<summary>Clique para expandir o Prompt</summary>

```text
Explique detalhadamente como o Python se integra com bancos de dados.
Foque em: PostgreSQL, SQLite e MongoDB.

Para cada banco, detalhe:
1. Driver/Biblioteca: Comando de instalação e nome no código.
2. String de Conexão: Padrão necessário (user, password, host).
3. Execução de Comandos: Como enviar comandos SQL ou NoSQL via Python.
4. Tratamento de Erros: Uso de try/except para resiliência de conexão.

Por fim, compare quando usar SQLite (local) vs PostgreSQL (servidor).
```
--- 
## 🩹 Cicatrizes

Ajuste de Rota: Durante os testes, percebi que se não especificarmos "Forneça apenas os enunciados" no Prompt 2, a IA resolve o exercício sozinha, o que anula o estudo. Adicionar essa restrição foi o que permitiu o aprendizado ativo.

---
## 🐍 Miniguia de Estudo: Python & Agentes de IA 

### 1. Resumos Estruturados

```text
A "Mente" do Python: O Python é uma linguagem de alto nível, interpretada e de tipagem dinâmica. Sua principal característica é a legibilidade extrema, imposta pela indentação obrigatória, que substitui as chaves {} de linguagens como Java ou C#. Isso força o desenvolvedor a escrever um código visualmente organizado e de fácil manutenção.

Modularização e Reuso: A linguagem permite dividir sistemas complexos em pacotes e módulos. Essa capacidade de componentização é vital para o desenvolvimento de software escalável, permitindo que diferentes funcionalidades sejam isoladas em arquivos independentes, facilitando testes unitários e o reaproveitamento de código em múltiplos sistemas.

A Transição para Agentes (ReAct): O aprendizado evoluiu da lógica procedural clássica para o modelo Reason + Act (Raciocínio + Ação). Neste paradigma, o Python atua como o cérebro de um sistema que não apenas processa dados, mas usa lógica para decidir dinamicamente qual ferramenta externa (banco de dados, APIs ou scripts de automação) deve ser invocada para resolver uma tarefa complexa.
```
### 📚 Glossário de Conceitos-Chave
| Termo | Definição |
| :--- | :--- |
| **PEP 8** | Guia de estilo oficial que define as melhores práticas de formatação para garantir que o código seja legível e padronizado. |
| **Tipagem Dinâmica** | Característica do Python onde o tipo da variável é definido em tempo de execução, sem necessidade de declaração explícita. |
| **Indentação** | Espaçamento obrigatório no início das linhas que define a estrutura e o escopo de blocos de código (substituindo as chaves {}). |
| **List Comprehension** | Sintaxe concisa para criar novas listas a partir de iteráveis, unindo loops e condições em uma única linha de código. |
| **Docstrings** | Strings literais usadas para documentar módulos, funções e classes, permitindo a geração automática de manuais.|
| **F-Strings** | Método de formatação de strings (f"texto {variavel}") que permite interpolar expressões de forma rápida e intuitiva. |
| **Paradigma POO** | Programação Orientada a Objetos; organiza o software em torno de dados (objetos) e lógica (métodos), usando herança e polimorfismo. |
| **ReAct (Reason + Act)** | Técnica que combina raciocínio lógico e execução de ações, permitindo que sistemas usem ferramentas externas para resolver tarefas. |
| **LLM Agent** | Implementação onde modelos de linguagem utilizam scripts (geralmente Python) para interagir com o mundo real e APIs. |

### 📑 Prompts Reutilizáveis para Revisão
Estes prompts foram refinados para apoiar futuras revisões ou expansões deste caderno temático:

**Prompt de Revisão Teórica:**
<details>
<summary>Clique para expandir o Prompt</summary>

```text
"Resuma os conceitos de Herança e Polimorfismo em Python, destacando as principais 
diferenças sintáticas em relação a linguagens de tipagem estática (como Java). 
Forneça um exemplo prático de Herança Múltipla."
```

**Prompt de Code Review:**
<details>
<summary>Clique para expandir o Prompt</summary>

```text
"Aja como um Engenheiro de Software Sênior. Analise o seguinte código Python:
[COLE SEU CÓDIGO AQUI]
Verifique a conformidade com a PEP 8 e sugira refatorações para melhorar 
a legibilidade e a performance."
````

**Prompt de Expansão de Conhecimento:**
<details>
<summary>Clique para expandir o Prompt</summary>
    
```text
"Explique o fluxo de um agente que utiliza a técnica ReAct (Reason + Act). 
Como o Python gerencia as 'ferramentas' (tools) que a IA pode decidir usar 
durante a execução de uma tarefa?"
```

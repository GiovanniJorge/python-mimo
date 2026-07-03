# Python - Mimo

Exercícios e projetos em linguagem Python usados nas aulas do curso "Python" da Mimo — coleção organizada com foco em aprendizagem prática de conceitos fundamentais. Ideal para estudantes que querem aprender ou consolidar conhecimentos em Python.

## Conteúdo principal
- Exercícios focados em problemas didáticos para aprendizagem de Python.
- Projetos práticos que exploram conceitos como lógica de programação, estruturas de dados e interação com o usuário.
- Exemplos claros com documentação em comentários e instruções de uso.

## Badges
![Licença](https://img.shields.io/github/license/GiovanniJorge/python-mimo?style=flat-square)
![Projetos](https://img.shields.io/badge/quantidade-7%20projetos-blue?style=flat-square)

## Sumário
- [Visão geral](#visão-geral)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Destaques do repositório](#destaques-do-repositório)
- [Como executar](#como-executar)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Autor / Contato](#autor--contato)

## Visão geral
Este repositório organiza pequenos programas e projetos em Python que exemplificam conceitos da linguagem e resolução de problemas práticos. Cada arquivo `.py` normalmente resolve um exercício específico ou implementa um projeto completo, e está escrito de forma didática com comentários explicativos.

Os projetos variam em complexidade, desde jogos interativos até sistemas de gerenciamento, permitindo aprender progressivamente.

## Estrutura do repositório
Top-level:
```text
├── .gitattributes
├── .gitignore
├── LICENSE
├── README.md
└── projetos-gerais/                   # Projetos e exercícios diversos desenvolvidos no curso
    ├── draw-a-card.py                 # Sorteia uma carta de baralho
    ├── food-order-system.py           # Sistema de pedidos de comida
    ├── library.py                     # Gerenciador de biblioteca
    ├── questions-bot.py               # Bot respondedor de perguntas
    ├── rock-paper-scissors-bot.py     # Jogo de Pedra, Papel, Tesoura
    ├── todo-list.py                   # Lista de tarefas (To-Do List)
    └── transaction-analyzer.py        # Analisador de transações financeiras
```

### Como se encaixa:
- O repositório abriga uma variedade de scripts e ferramentas independentes criados ao longo do curso.
- Cada arquivo `.py` funciona como um programa executável autônomo. A dinâmica comum de uso consiste em disparar o arquivo desejado diretamente pelo terminal, interagindo com as entradas e saídas (I/O) nativas do console.

## Destaques do repositório

### Food Order System
* **Descrição:** Fluxo interativo baseado em terminal para montagem e cálculo de combos em um restaurante virtual.
* **Conceitos:** Condicionais, laços de repetição e manipulação de listas.

### Library Manager
* **Descrição:** Pequeno gerenciador capaz de controlar acervos de livros, estados de empréstimos e registros de usuários.
* **Conceitos:** Dicionários (dicts), funções e persistência volátil em memória.

### Transaction Analyzer
* **Descrição:** Script utilitário voltado ao processamento de listas financeiras para extração de médias, maiores despesas e balanços consolidados.
* **Conceitos:** Estruturas de dados complexas, list comprehensions e funções built-in.

## Como executar

### Pré-requisitos
- **Python** (v3.6 ou superior instalado)
- Terminal de comandos ou prompt configurado no path global

### Passos para execução

1. **Clone o repositório:**
```bash
git clone [https://github.com/GiovanniJorge/python-mimo.git](https://github.com/GiovanniJorge/python-mimo.git)
cd python-mimo
```

2. **Execute o script desejado diretamente pelo interpretador (Exemplo com o Pedra, Papel, Tesoura):**
```bash
python projetos-gerais/rock-paper-scissors-bot.py
```

> **Nota:** Caso o seu sistema possua aliases diferentes mapeados, você pode precisar forçar a execução chamando explicitamente por `python3 projetos-gerais/rock-paper-scissors-bot.py`. Para checar seu ambiente atual, execute `python --version`.

## Contribuindo
Contribuições são bem-vistas! Se deseja adicionar um novo jogo de terminal ou otimizar rotinas de list comprehensions, siga os passos abaixo:

1. Faça um **Fork** do repositório.
2. Crie uma branch com nome descritivo: `feature/novo-projeto` ou `fix/correcao-nome`.
3. Faça commits atômicos com mensagens claras e objetivas seguindo as diretrizes da comunidade.
4. Abra um **Pull Request** detalhando as alterações implementadas.

## Licença
Este repositório utiliza a licença MIT — consulte o arquivo [LICENSE](LICENSE) na raiz.

## Autor / Contato
- **Autor:** Giovanni Jorge  
- **Repositório:** [https://github.com/GiovanniJorge/python-mimo](https://github.com/GiovanniJorge/python-mimo)

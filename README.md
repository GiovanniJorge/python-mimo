# Python - Mimo
Exercícios e projetos em linguagem Python usados nas aulas do curso "Python" da Mimo — coleção organizada com foco em aprendizagem prática de conceitos fundamentais. Ideal para estudantes que querem aprender ou consolidar conhecimentos em Python.

## Conteúdo principal
- Exercícios focados em problemas didáticos para aprendizagem de Python.
- Projetos práticos que exploram conceitos como lógica de programação, estruturas de dados e interação com o usuário.
- Exemplos claros com documentação em comentários e instruções de uso.

## Badges
- Licença: MIT (ver arquivo LICENSE)

## Sumário
- [Visão geral](#visão-geral)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Como executar](#como-executar)
- [Boas práticas / recomendações](#boas-práticas--recomendações)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Autor / Contato](#autor--contato)

## Visão geral
Este repositório organiza pequenos programas e projetos em Python que exemplificam conceitos da linguagem e resolução de problemas práticos. Cada arquivo `.py` normalmente resolve um exercício específico ou implementa um projeto completo, e está escrito de forma didática com comentários explicativos.

Os projetos variam em complexidade, desde jogos interativos até sistemas de gerenciamento, permitindo aprender progressivamente.

## Estrutura do repositório
```
.
├── .gitattributes
├── .gitignore
├── LICENSE
├── README.md
└── projetos-gerais/                    — Projetos e exercícios diversos
    ├── draw-a-card.py                 — Projeto: Sorteia uma carta de baralho
    ├── food-order-system.py           — Projeto: Sistema de pedidos de comida
    ├── library.py                     — Projeto: Gerenciador de biblioteca
    ├── questions-bot.py               — Projeto: Bot respondedor de perguntas
    ├── rock-paper-scissors-bot.py     — Projeto: Jogo de Pedra, Papel, Tesoura
    ├── todo-list.py                   — Projeto: Lista de tarefas (To-Do List)
    └── transaction-analyzer.py        — Projeto: Analisador de transações financeiras
```

Como se encaixa:
- Cada arquivo `.py` é um programa independente (exercício ou projeto). A forma usual de usar o repositório é executar o arquivo que você quer testar.
- Os projetos são autoexplicativos e geralmente incluem interação via terminal (input/output).
- Cada projeto implementa conceitos específicos de Python (funções, dicionários, listas, laços, condicionais, etc.).

## Como executar

### Pré-requisitos
- Python 3.6 ou superior instalado em sua máquina.
- Um terminal ou prompt de comando.

### Executar um projeto
Para executar qualquer um dos projetos, navegue até o diretório e use:

```bash
python nome_do_arquivo.py
```

Exemplos:

```bash
# Executar o jogo de Pedra, Papel, Tesoura
python projetos-gerais/rock-paper-scissors-bot.py

# Executar o sistema de pedidos
python projetos-gerais/food-order-system.py

# Executar a lista de tarefas
python projetos-gerais/todo-list.py
```

### Verificar a versão do Python
```bash
python --version
```

Se o comando não funcionar, tente:
```bash
python3 --version
```

## Boas práticas / recomendações

### Desenvolvimento
- Use nomes descritivos para variáveis e funções.
- Mantenha o código limpo e legível com espaçamento adequado.
- Documente cada projeto no topo do arquivo com comentários explicando:
  - O objetivo do programa
  - Como executá-lo
  - Exemplo de entrada/saída esperada

### Execução
- Sempre teste o código antes de fazer commit.
- Verifique se o código é compatível com Python 3.6+.
- Para debugging, use `print()` estrategicamente ou ferramentas como `pdb`.

### Padrões de código
- Siga a convenção PEP 8 para nomenclatura e formatação.
- Use comentários para explicar lógica complexa.
- Prefira nomes de arquivos em minúsculas com hífens (ex: `rock-paper-scissors.py`) para compatibilidade.

### Validação opcional
- Considere usar `flake8` ou `pylint` para verificar qualidade do código:
  ```bash
  pip install flake8
  flake8 projetos-gerais/
  ```

## Contribuindo
Contribuições são bem-vindas (ex.: novos projetos, melhorias, correções, testes). Fluxo sugerido:

1. Fork do repositório.
2. Criar branch com nome descritivo: `feature/novo-projeto` ou `fix/correcao-nome`.
3. Fazer commits atômicos com mensagens claras.
4. Abrir Pull Request descrevendo as mudanças e, se aplicável, o conceito Python explorado.
5. Se possível, inclua:
   - Uma breve descrição do projeto no topo do arquivo.
   - Exemplos de entrada/saída esperada.
   - Comentários explicando trechos de código importantes.

Sugestões adicionais:
- Se adicionar novo tipo de projeto, organize em subpastas temáticas (ex: `jogos/`, `sistemas/`, `analise-dados/`).
- Adicione um pequeno comentário no topo de cada novo arquivo explicando seu propósito.

## Testes e automação (opcional)
- Considere adicionar um `Makefile` com targets como `make test`, `make lint`, `make run`.
- Para verificação automática, adicionar um workflow (GitHub Actions) que valida cada `.py` com `python -m py_compile` para garantir sintaxe correta.

## Licença
Este repositório utiliza a licença MIT — consulte o arquivo `LICENSE` na raiz.

## Autor / Contato
Autor: Giovanni Jorge  
Repositório: https://github.com/GiovanniJorge/python-mimo

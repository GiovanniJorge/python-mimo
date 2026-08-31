# Python - Mimo

<p align="center">
    <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white" alt="Python"></a>
    <a href="#"><img src="https://img.shields.io/badge/status-concluído-brightgreen" alt="Status"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/Licença-MIT-blue?logo=github&logoColor=white" alt="Licença"></a>
    <a href="https://github.com/GiovanniJorge/python-mimo"><img src="https://img.shields.io/badge/Projetos-7-4A90E2?logo=github&logoColor=white" alt="Projetos"></a>
</p>

## Sumário

- [Descrição do Projeto](#descrição-do-projeto)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Como Executar Localmente](#como-executar-localmente)
- [Uso e Exemplos](#uso-e-exemplos)
- [Troubleshooting / FAQ](#troubleshooting--faq)
- [Contribuição](#contribuição)
- [Autor](#autor)
- [Licença](#licença)

## Descrição do Projeto

Este repositório reúne uma coleção de exercícios e pequenos projetos em Python desenvolvidos durante o curso “Python” da Mimo. O objetivo principal é praticar conceitos fundamentais da linguagem por meio de scripts simples, interativos e didáticos, com foco em lógica de programação, estruturas de dados e uso do terminal.

Os arquivos presentes neste projeto abordam temas como processamento de entradas do usuário, manipulação de listas, criação de jogos e sistemas de console. Cada script é autônomo, fácil de compreender e pode ser executado diretamente pelo interpretador Python, tornando o material útil tanto para aprendizado quanto para revisão de conceitos básicos.

## Estrutura do Repositório

A organização do projeto é simples e direta:

```text
python-mimo/
├── LICENSE
├── README.md
├── .gitignore
├── .gitattributes
└── projetos-gerais/
    ├── draw-a-card.py
    ├── food-order-system.py
    ├── library.py
    ├── questions-bot.py
    ├── rock-paper-scissors-bot.py
    ├── todo-list.py
    └── transaction-analyzer.py
```

### Explicação dos principais diretórios e arquivos

- `projetos-gerais/`: contém os scripts Python do repositório, cada um com um objetivo específico e independente.
- `README.md`: documentação principal do projeto.
- `LICENSE`: texto da licença MIT do repositório.
- `draw-a-card.py`: simula o sorteio de cartas de baralho.
- `food-order-system.py`: sistema interativo de pedidos de comida no terminal.
- `library.py`: exercício de gerenciamento de biblioteca e livros.
- `questions-bot.py`: chatbot simples com perguntas e respostas.
- `rock-paper-scissors-bot.py`: jogo de pedra, papel e tesoura contra o computador.
- `todo-list.py`: lista de tarefas interativa.
- `transaction-analyzer.py`: análise básica de transações financeiras.

### Fluxo de trabalho

O fluxo do projeto é bem simples: o usuário escolhe o script desejado e executa o arquivo com Python no terminal. Cada script recebe entradas do usuário por meio de `input()`, processa lógica interna e gera saídas no console. Não existe camada de banco de dados, API ou frontend; a comunicação é direta com o ambiente do terminal.

## Como Executar Localmente

### Pré-requisitos

- Python 3.8 ou superior
- Terminal ou prompt de comando
- Git (opcional, para clonar o repositório)

### Configuração de Ambiente

Este projeto não utiliza arquivos `.env`, variáveis de ambiente ou dependências externas. A execução depende apenas da instalação do Python e do terminal do sistema operacional.

### Instalação

1. Clone o repositório:

```bash
git clone https://github.com/GiovanniJorge/python-mimo.git
cd python-mimo
```

2. Verifique se o Python está instalado:

```bash
python --version
```

Se o comando não for reconhecido, teste:

```bash
python3 --version
```

### Execução

Cada script pode ser executado diretamente:

```bash
python projetos-gerais/rock-paper-scissors-bot.py
```

Exemplos:

```bash
python projetos-gerais/draw-a-card.py
python projetos-gerais/food-order-system.py
python projetos-gerais/library.py
python projetos-gerais/todo-list.py
python projetos-gerais/transaction-analyzer.py
```

> Em alguns ambientes Windows, o comando pode ser `py` em vez de `python`.

## Uso e Exemplos

Após iniciar um script, o programa geralmente solicita entradas pelo terminal e responde com resultados diretamente no console. A interação é textual e segue o fluxo do próprio programa.

### Exemplos de uso

- Jogo de cartas:
  - execute `draw-a-card.py`
  - informe quantas cartas deseja receber

- Sistema de pedidos:
  - execute `food-order-system.py`
  - escolha o tipo de comida e o prato desejado

- Lista de tarefas:
  - execute `todo-list.py`
  - adicione, remova ou visualize tarefas

- Jogo Pedra, Papel e Tesoura:
  - execute `rock-paper-scissors-bot.py`
  - escolha entre pedra, papel ou tesoura

## Troubleshooting / FAQ

### 1. O comando `python` não é reconhecido
Tente usar:

```bash
python3 --version
```

ou, no Windows:

```bash
py --version
```

### 2. O script não inicia corretamente
Confirme se você está na pasta raiz do projeto e usou o caminho correto do arquivo:

```bash
python projetos-gerais/nome-do-arquivo.py
```

### 3. Erro de sintaxe
Verifique se o arquivo foi salvo corretamente com extensão `.py` e que o código não foi alterado indevidamente.

### 4. Nenhuma dependência externa foi instalada
Isso é esperado: o projeto usa exclusivamente a biblioteca padrão do Python, então não há instalação adicional de pacotes.

## Contribuição

Contribuições são bem-vindas. Se você quiser colaborar com melhorias, novos exercícios ou ajustes na documentação, siga os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma branch para a sua mudança:
   ```bash
   git checkout -b feature/nova-funcionalidade
   ```
3. Faça commits claros e objetivos.
4. Abra um Pull Request com descrição detalhada das alterações.

## Autor

- Nome: Giovanni Jorge
- GitHub: [@GiovanniJorge](https://github.com/GiovanniJorge)

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` na raiz do repositório para mais detalhes.

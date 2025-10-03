# Sistema Simples de Cadastro em Python

Um sistema básico de **cadastro de pessoas** desenvolvido em Python, utilizando arquivos de texto para persistência de dados.

---

## Funcionalidades

Este sistema oferece as seguintes opções através de um menu interativo no terminal:

1.  **Ver pessoas Cadastradas**: Exibe a lista de nomes e idades previamente registradas.
2.  **Cadastrar nova Pessoa**: Permite adicionar um novo nome e idade ao registro.
3.  **Sair do Sistema**: Encerra a aplicação.

## Estrutura do Projeto

O código está dividido em dois arquivos:

* **Arquivo Principal `sistema.py`:** Contém a lógica principal do programa, o laço do menu e a chamada das funções.
* **`lib/interface.py` (ou arquivo de funções):** Contém as funções de interface (menu, cabeçalhos, leitura de input seguro `leiaInt`) e as funções de manipulação de arquivo (`arquivoExiste`, `criarArquivo`, `lerArquivo`, `cadastrar`).


---

## Detalhes Técnicos

* Os dados de cadastro são salvos em um arquivo de texto chamado **`curso.txt`** no mesmo diretório de execução.
* As entradas do usuário para idade são validadas para aceitar apenas números inteiros.
* Mensagens coloridas (escapes ANSI) são usadas para melhorar a experiência no terminal.

---

🧑‍💻 Autor
Crysthofer

📜
Este projeto está sob a licença MIT.

©2025 Crysthofer

# 🤖 Agente de Automação: Integração Trello & Python

[![DIO - Education](https://img.shields.io/badge/DIO-Education-red)](https://www.dio.me/)
[![Nível - Básico](https://img.shields.io/badge/Nível-Básico-green)](#)

## 📋 Descrição do Projeto
Este repositório foi desenvolvido para o desafio de projeto da DIO, com foco na criação de um **Agente de Automação** utilizando Python. O sistema é capaz de interagir com a API do Trello para organizar, automatizar e otimizar fluxos de trabalho (workflows).

O objetivo principal é explorar a lógica de automação, manipulação de APIs externas e a estruturação de agentes que facilitam a gestão de tarefas e a produtividade.

## 🚀 Tecnologias Utilizadas
* **Python 3.7+**
* **API do Trello** (Power-Up para automação de boards)
* **Requests:** Biblioteca para chamadas HTTP.
* **Python-dotenv:** Gerenciamento seguro de credenciais.

## 📂 Estrutura do Agente
O projeto está organizado na pasta `agent04`, contendo:
* **`agenttaskmanager/`**: Módulo responsável pela lógica de manipulação de cartões e listas.
* **`requirements.txt`**: Lista de dependências para o funcionamento do agente.
* **`readme.md`**: Guia de configuração da API (Registro e Autorização).

## 🛠️ Como Configurar e Usar
1.  **Fork e Clone:** Realize o fork deste repositório e clone em sua máquina.
2.  **Obter Credenciais:**
    * Acesse o [Trello Power-Up Admin](https://trello.com/power-ups/admin).
    * Gere sua **API Key** e seu **Token**.
3.  **Variáveis de Ambiente:** Crie um arquivo `.env` na raiz:
    ```env
    TRELLO_API_KEY=sua_chave_aqui
    TRELLO_TOKEN=seu_token_aqui
    ```
4.  **Execução:**
    ```bash
    pip install -r requirements.txt
    python main.py
    ```

## 👨‍💻 Desenvolvedor
* **Dimas Alves**
* [LinkedIn](https://linkedin.com/in/dimas-alves-50b715176)
* [GitHub](https://github.com/dimasreisalves/agente-automacao-trello)

---
*Projeto desenvolvido como parte do desafio de automação com IA e Python da DIO.*

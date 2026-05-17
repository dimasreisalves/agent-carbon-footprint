# 🤖 Agente de Automação: Gerenciamento de Tarefas e Cálculo de Carbono

[![DIO - Education](https://img.shields.io/badge/DIO-Education-red)](https://www.dio.me/)
[![Nível - Básico](https://img.shields.io/badge/Nível-Básico-green)](#)

## 📋 Descrição do Projeto
Este repositório contém o desenvolvimento de um agente inteligente em Python, focado na automação de fluxos de trabalho. O projeto integra a API do **Trello** para gestão de tarefas com uma lógica de inteligência artificial aplicada ao cálculo e análise de pegada de carbono (**Agent Carbon Footprint**).

O objetivo é demonstrar como agentes podem orquestrar tarefas complexas, desde a entrada de dados (Intake) até o aconselhamento estratégico (Advisor).

## 🚀 Tecnologias Utilizadas
* **Python 3.7+**
* **API do Trello** (para gerenciamento das demandas)
* **Bibliotecas Python:** `requests`, `python-dotenv`
* **Framework de Agentes:** Baseado na estrutura orquestrada da DIO.

## 📂 Estrutura de Agentes (agent04)
O projeto é dividido em módulos especializados:
1.  **Orquestrador:** Gerencia o fluxo entre os agentes.
2.  **Intake:** Coleta os dados iniciais.
3.  **Factors:** Identifica os fatores de emissão.
4.  **Calculator:** Realiza os cálculos matemáticos.
5.  **Advisor:** Sugere melhorias e planos de ação.

## 🛠️ Como Configurar e Usar
1.  **Fork e Clone:** Realize o fork deste repositório e clone em sua máquina.
2.  **Dependências:** Instale os requisitos necessários:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Variáveis de Ambiente:** Crie um arquivo `.env` com suas credenciais do Trello:
    ```env
    TRELLO_API_KEY=sua_chave_aqui
    TRELLO_TOKEN=seu_token_aqui
    ```
4.  **Execução:** Rode o script principal para iniciar a automação.

## 👨‍💻 Desenvolvedor
* **Seu Nome Aqui**
* [Seu LinkedIn](https://linkedin.com/in/seu-perfil)
* [Seu Portfólio/GitHub](https://github.com/seu-usuario)

---
*Projeto desenvolvido como parte do desafio de Agentes de IA da DIO.*

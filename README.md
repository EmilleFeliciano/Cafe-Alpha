# ☕Cafe-Alpha

## Projeto desenvolvido durante a Imersão de IA da Alura, com foco na criação de um bot integrado ao Google Gemini, utilizando Google AI Studio e N8N para automação de fluxos inteligentes.

📌 Visão Geral

O Cafe-Alpha é um projeto experimental que demonstra a integração entre:

- IA Generativa (Google Gemini)

- Automação de fluxos com N8N

- Interface web simples em HTML

- Integração com APIs externas

O sistema utiliza um bot alimentado pelo Gemini, capaz de processar entradas e gerar respostas inteligentes, com automações estruturadas no N8N para orquestração do fluxo.

🧠 Arquitetura da Solução

Usuário → Interface Web → Webhook N8N → Google Gemini API → Resposta Automatizada

Componentes:

Frontend (HTML)
- Interface básica para interação com o bot.

N8N
Responsável por:
- Receber requisições via webhook
- Processar entradas
- Enviar requisição para a API do Gemini
- Retornar resposta ao usuário

Google Gemini (via AI Studio)
- Responsável pela geração das respostas utilizando IA generativa.

🚀 Tecnologias Utilizadas

- HTML
- Google Gemini API
- Google AI Studio
- N8N
- Webhooks
- Integração com APIs REST

🔎 Funcionalidades

- Integração com modelo de IA generativa
- Automação de fluxo via N8N
- Comunicação via webhook
- Processamento de requisições e respostas dinâmicas
- Estrutura modular para expansão futura

📂 Estrutura do Projeto
Cafe-Alpha/
│
├── index.html
├── img/
└── README.md

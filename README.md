# 📋 Cadastro de Clientes

Formulário de cadastro de clientes com integração automática ao Google Sheets e notificação por e-mail.

## 🚀 Funcionalidades

- Formulário responsivo com tema escuro
- Campos validados (nome e WhatsApp obrigatórios)
- Seleção de tipo de pacote, dispositivo e local de instalação
- Suporte a múltiplos pontos de instalação
- Integração com Google Sheets via Apps Script
- Notificação por e-mail a cada novo cadastro
- Botão de contato via WhatsApp

## 🛠️ Tecnologias

- HTML5 + CSS3 + JavaScript
- Google Apps Script
- Google Sheets
- Netlify

## ⚙️ Como usar

1. Faça o download do arquivo `cadastro-clientes.html`
2. No Google Sheets crie uma planilha com os cabeçalhos: `Nome, Email, WhatsApp, Local, Qtd Pontos, Instalação, Acesso, Pacote, Obs, Data`
3. Crie um Apps Script vinculado à planilha com a função `doPost`
4. Publique o script como App da Web e copie a URL
5. Substitua a URL no arquivo HTML
6. Hospede o arquivo em qualquer serviço como Netlify

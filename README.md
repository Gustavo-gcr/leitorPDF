# 🏦 Extrator de Saldo Diário de Extratos

Projeto desenvolvido para automatizar e otimizar a rotina de conciliação bancária/contábil no meu ambiente de trabalho.

## 🎯 Objetivo

Esta aplicação Streamlit tem como finalidade principal processar grandes volumes de extratos bancários ou contábeis (em formato PDF) de forma eficiente. O objetivo é extrair automaticamente a data e o valor do **"Saldo do Dia"** (ou variações desta frase) para gerar uma planilha unificada, agilizando o processo de conciliação diária e fechamento.

## ✨ Funcionalidades

| Ícone | Funcionalidade | Descrição |
| :---: | :--- | :--- |
| ⬆️ | **Upload Múltiplo** | Permite o upload de um ou mais arquivos PDF simultaneamente. |
| 🔍 | **Extração Inteligente** | Utiliza `pdfplumber` e Expressões Regulares (Regex) para localizar a expressão "Saldo do dia" (case-insensitive) e seu valor associado. |
| 📅 | **Captura de Data** | Identifica a data do extrato, mesmo que não esteja adjacente ao saldo. |
| 📊 | **Geração de Relatório** | Cria e exibe um DataFrame Pandas com os resultados. |
| 💾 | **Download Excel** | Disponibiliza um botão para baixar a planilha consolidada em formato `.xlsx`. |
| ⚠️ | **Registro de Falhas** | Isola e reporta os arquivos onde o saldo não pôde ser encontrado para revisão manual. |

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído usando as seguintes ferramentas e bibliotecas Python:

| Ferramenta | Uso |
| :--- | :--- |
| **Python** | Linguagem de Programação Principal. |
| **Streamlit** | Criação da interface de usuário interativa (Web App). |
| **pdfplumber** | Extração robusta de texto de PDFs. |
| **pandas** | Manipulação, estruturação dos dados e criação do DataFrame. |
| **openpyxl** | Motor para exportação do DataFrame para o formato `.xlsx` (Excel). |

## ⚙️ Como Executar o Projeto

### Entrar no link abaixo


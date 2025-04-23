# 💧 Sistema de Irrigação (Simples)

Projeto desenvolvido como parte do curso de **Análise e Desenvolvimento de Sistemas**, com o objetivo de praticar conceitos fundamentais de **Python** e **SQLite**, por meio de um sistema de controle de irrigação simples e funcional.

---

## 🎯 Objetivo

Criar um sistema básico onde o usuário, após se cadastrar com uma chave de acesso, pode **ligar ou desligar a irrigação** com um clique de botão, simulando o controle de um sistema automatizado de irrigação.

---

## 🧪 Funcionalidades

- ✅ Cadastro de usuários com chave de acesso por tipo
- 🔐 Login básico com nome de usuário e senha
- 💧 Botão para **ligar/desligar irrigação**
- 🗃️ Banco de dados em **SQLite** para armazenar usuários e ações

---

## 🔑 Chaves de Cadastro

| Chave        | Tipo de Usuário |
|--------------|-----------------|
| `CHAVE-123`  | USUÁRIO         |
| `CHAVE-456`  | DEV             |
| `CHAVE-789`  | ADM             |

> Essas chaves são obrigatórias para criar a conta no sistema.

---

## 💻 Tecnologias Utilizadas

- 🐍 **Python 3**
- 🗄️ **SQLite3**
- 🧠 Lógica de Programação (condições, funções, variáveis)
- 📁 Manipulação de arquivos (se aplicável)

---

## 🚀 Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/1rodrigueX/projetotreinopy-sql.git
cd sistema-irrigacao
```

## 📁 Estrutura do Projeto
graphql
Copiar
Editar
```
sistema-irrigacao/
├── main.py               # Código principal com lógica de login e controle de irrigação
├── banco.db              # Banco de dados SQLite com tabela de usuários
├── criar_executavel.bat  # (opcional) Script para gerar o .exe
└── README.md             # Documentação do projeto
```
## 🧠 Propósito Educacional
Este projeto é didático, voltado para o aprendizado de:

Interação com banco de dados SQLite via Python

Autenticação de usuários

Lógica simples de ativação de sistemas (liga/desliga)
```
Uso de chaves de acesso por nível de usuário

# 🚀 Tutorial – Instalação do MongoDB no Windows

Este repositório contém um guia simples e direto para instalar o **MongoDB Community Edition** no Windows.

Ideal para iniciantes que estão começando com banco de dados NoSQL ou precisam configurar o ambiente local para estudos e projetos.

---

## 📌 Sobre o MongoDB

O **MongoDB** é um banco de dados **NoSQL orientado a documentos**, que armazena dados em formato JSON (internamente BSON).

🔹 Modelo flexível  
🔹 Alta performance  
🔹 Muito utilizado em aplicações modernas  
🔹 Integra facilmente com Node.js, Java, Python e outras tecnologias  

---

## 🛠️ Requisitos

Antes de começar, você precisa:

- ✔ Windows 10 ou superior
- ✔ Acesso à internet
- ✔ Permissão para instalar programas no computador

---

## 📥 Passo 1 – Download do MongoDB

1. Acesse o site oficial:  
   👉 https://www.mongodb.com/try/download/community

2. Selecione:
   - **Version:** Última versão disponível
   - **Platform:** Windows
   - **Package:** msi

3. Clique em **Download**

---

## 💻 Passo 2 – Executando o Instalador

1. Abra o arquivo `.msi` baixado.
2. Clique em **Next**
3. Aceite os termos da licença
4. Continue clicando em **Next**

---

## ⚙️ Passo 3 – Tipo de Instalação

1. Escolha a opção **Complete (Recomendado)**
2. Clique em **Next**

Na tela seguinte:

✔ Marque **Install MongoDB as a Service**  
✔ Marque **Run service as Network Service user**

Isso permitirá que o MongoDB inicie automaticamente junto com o Windows.

Finalize clicando em:

**Install → Finish**

---

## ✅ Passo 4 – Verificando a Instalação

1. Pressione `Windows + R`
2. Digite `cmd`
3. No terminal, execute:

```bash
mongosh

Se aparecer algo como:

test>

🎉 Parabéns! O MongoDB está funcionando corretamente.

🧪 Testando um Comando

Dentro do mongosh, execute:

show dbs

Para sair:

exit
📌 Porta Padrão

O MongoDB roda localmente por padrão na porta:

27017
📂 Estrutura do Projeto
📁 tutorial-mongodb-windows
 ├── README.md
 └── tutorial_mongodb_windows.txt
🎯 Objetivo do Tutorial

Este material foi criado para:

Auxiliar iniciantes

Servir como documentação rápida

Apoiar estudos de banco de dados

Facilitar configuração de ambiente local

👨‍💻 Autor

Gabriel Teodoro
Estudante de Desenvolvimento de Software
Foco em Back-end Java | Banco de Dados | Arquitetura de Software

⭐ Contribuição

Se este tutorial te ajudou, considere:

Dar uma ⭐ no repositório

Compartilhar com outros desenvolvedores iniciantes

📜 Licença

Este projeto é livre para uso educacional.

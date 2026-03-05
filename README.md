# 📘 Projeto de Sistema Computacional - " digite aqui o nome do seu sistema "
<img width="192" height="89" alt="image" src="https://github.com/user-attachments/assets/9f00c432-def4-4de7-8b12-439b34ca8b9c" />

Curso: Superior de Tecnologia em Análise e Desenvolvimento de Sistemas

Disciplina: Análise e Projeto de Sistemas

Orientador: Prof. Me. Denys Alves da Silva

Nome do grupo: 

Alunos: RA Nome completo e-mail sempreceub


---

## 📑 Sumário
1. [Briefing](#0-briefing)
2. [Documento de Visão do Sistema](#1-documento-de-visão-do-sistema)  
3. [Diagrama de Caso de Uso](#2-diagrama-de-caso-de-uso)  
4. [Especificação de Caso de Uso](#3-especificação-de-caso-de-uso)  
5. [Diagrama de Classe](#4-diagrama-de-classe)  
6. [Documento de Arquitetura do Sistema](#5-documento-de-arquitetura-do-sistema)  
7. [Protótipo do Sistema](#6-protótipo-do-sistema)  

---
# 
**Orientações de cada tópico da Análise e Projeto de Sistema.**  

A equipe deverá ajustar este modelo para o seu projeto.   

Deve manter no mínimo os tópicos que estão no sumário.  

Na entrega final, a equipe deve excluir estas orientações, ficando apenas o cabeçalho e o sumário neste REAME.md, e os arquivos .md de cada tópico no repositório.  

# 


## 0. Briefing
Um briefing é um documento curto e claro que reúne todas as informações necessárias para orientar a equipe no início do projeto. 
Ele evita divergências e garante que todos entendam o que será feito, por quê, para quem e como.
Segue a estrutura do Briefing para o projeto.

**1 - Informações gerais**  
1.1 - Nome do sistema:  
1.2 - Nome da equipe:  

**2 - Problema e/ou necessidade**  (explique claramente)  
2.1 - Qual é o problema e/ou necessidade que o software deve resolver:  
2.2 - Quais são as dores dos usuários:  
2.3 - O que acontece hoje sem o sistema:  

**3 - Escopo funcional do sistema** (O que o sistema deve fazer)    
3.1 - Principal objetivo do sistema:  
3.2 - Funcionalidades específicas (secundárias) do sistema:  

**4. Escopo não funcional** (Liste os critérios técnicos e de qualidade)   

**5. Usuários** (Liste os principais usuário do sistema)    

**6. Entregáveis** (Manter os artefatos abaixo. Não é necessário editar este tópico)
• Documento de Visão do Sistema  
• Diagrama de Caso de Uso  
• Especificação de Caso de Uso  
• Diagrama de Classe  
• Documento de Arquitetura do Sistema  
• Protótipo do Sistema  

## 1. Documento de Visão do Sistema

📌 **O que é:**  
Documento inicial que descreve **objetivos, escopo, usuários e restrições** do sistema.  

📌 **Como preencher:**  
- Introdução: breve resumo do sistema.  
- Objetivos do sistema: problemas que resolve.  
- Stakeholders: usuários e clientes.  
- Escopo: principais funcionalidades.  
- Restrições: limitações técnicas, prazos etc.  
- Critérios de sucesso: como medir se o sistema atendeu ao objetivo.  

---

## 2. Diagrama de Caso de Uso

📌 **O que é:**  
Representação UML das **funcionalidades principais** e **atores envolvidos**.  

📌 **Como preencher:**  
- Identificar os atores (usuário, administrador, sistemas externos).  
- Identificar os casos de uso (funcionalidades).  
- Criar o diagrama em UML (PlantUML, Lucidchart, StarUML, Draw.io).  

📄 **Exemplo de atores e casos de uso:**  
- Atores: Usuário, Bibliotecário.  
- Casos de Uso: Realizar Login, Consultar Livro, Efetuar Empréstimo, Cadastrar Livro.  

📷 **Adicionar aqui o diagrama:**  


---

## 3. Especificação de Caso de Uso

📌 **O que é:**  
Descrição detalhada do **fluxo principal e alternativo** de cada caso de uso.  

📌 **Modelo de Tabela:**  

| Item                  | Descrição |
|-----------------------|-----------|
| **Nome**              | Realizar Login |
| **Ator Principal**    | Usuário |
| **Pré-condições**     | Usuário já cadastrado no sistema |
| **Fluxo Principal**   | 1. Usuário insere login e senha <br> 2. Sistema valida credenciais <br> 3. Sistema libera acesso |
| **Fluxos Alternativos** | Senha incorreta → Sistema exibe mensagem de erro |
| **Pós-condições**     | Usuário autenticado no sistema |
| **Regras de negócio** | Senha deve ter no mínimo 8 caracteres |

📄 Criar uma tabela como esta **para cada caso de uso** identificado.

---

## 4. Diagrama de Classe

📌 **O que é:**  
Representação estática em UML das **classes, atributos, métodos e relacionamentos**.  

📌 **Como preencher:**  
- Listar classes principais (Ex.: Usuário, Livro, Empréstimo).  
- Definir atributos e métodos.  
- Relacionar com UML (herança, associação, composição, agregação).  

📷 **Adicionar aqui o diagrama:**  



---

## 5. Documento de Arquitetura do Sistema

📌 **O que é:**  
Definição da **estrutura técnica** do sistema.  

📌 **Como preencher:**  
- Visão geral da arquitetura (camadas ou microsserviços).  
- Tecnologias utilizadas (linguagem, frameworks, banco de dados).  
- Integrações externas (APIs, serviços).  
- Segurança (autenticação, criptografia).  
- Requisitos de desempenho e escalabilidade.  

📄 **Exemplo (preencher no projeto real):**  
Arquitetura em 3 camadas:

Apresentação (JavaFX ou ReactJS)

Negócio (Java - Spring Boot)

Persistência (MySQL)

Integrações: API de Pagamento
Segurança: Autenticação com JWT

---

## 6. Protótipo do Sistema

📌 **O que é:**  
Protótipo visual ou navegável que representa a interface do sistema.  

📌 **Como preencher:**  
- Criar esboços das telas principais (login, cadastro, dashboard).  
- Pode ser feito no **Figma, Balsamiq, Draw.io ou PowerPoint**.  
- Salvar em PDF ou imagem.  

📷 **Adicionar protótipo aqui:**  


---

## ✅ Organização no GitHub
Estrutura de diretórios sugerida:

Arquivos de Markdown do GitHub para o aluno utilizar obrigatoriamente no seu projeto.

├── [0. Briefing](00-briefing.md)

├── [1. Documento de Visão do Sistema](01-visao-sistema.md)

├── [2. Diagrama de Caso de Uso](02-diagrama-caso-uso.md)

├── [3. Especificação de Caso de Uso](03-especificacao-caso-uso.md)

├── [4. Diagrama de Classe](04-diagrama-classes.md)

├── [5. Documento de Arquitetura do Sistema](05-arquitetura-sistema.md)

├── [6. Protótipo do Sistema](06-prototipo.md)

---

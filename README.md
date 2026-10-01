# 🏆 Sistema de Gerenciamento de Hackathon

> Projeto desenvolvido para a disciplina de Engenharia de Software.

---

## 📌 Descrição do Projeto

O Sistema de Gerenciamento de Hackathon é uma solução desenvolvida no âmbito da disciplina de Engenharia de Software com o objetivo de automatizar, organizar e otimizar todas as etapas de execução de um hackathon acadêmico.

A plataforma atua como um ponto centralizador para a dinamização do evento, garantindo fluidez na comunicação entre participantes, comissão avaliadora e a organização.

---

## 🚀 Funcionalidades

### 👥 Módulo de Participantes e Equipes
- **Autenticação e Perfil:** Cadastro de alunos e login seguro.
- **Formação de Times:** Criação de equipes, definição do nome/tema do time e gerenciamento de integrantes.
- **Painel da Equipe:** Visualização dos membros, status da submissão e prazos do evento.

### 📤 Módulo de Submissão de Projetos
- **Envio de Links:** Upload/envio de URLs do repositório (GitHub/GitLab), protótipo (Figma) e vídeo demonstrativo.

### 📝 Módulo da Comissão Avaliadora
- **Painel do Avaliador:** Lista de projetos atribuídos para análise.
- **Avaliação e Comentários:** Campo para inserção de pareceres técnicos, feedbacks estruturados e notas/pontuações por critério.
- **Histórico de Feedbacks:** Organização e centralização de todos os comentários enviados às equipes.

### 👑 Módulo Administrativo / Organização
- **Controle de Prazos:** Abertura e encerramento das janelas de submissão.
- **Gestão da Banca:** Atribuição de avaliadores às equipes.
- **Classificação:** Consolidação das notas e geração do ranking final do hackathon.

---

## 🛠️ Tecnologias Utilizadas

- **Frontend:** React.js / HTML5 + CSS
- **Backend:** Node.js
- **Banco de Dados:** MySQL
- **Autenticação:** JWT (JSON Web Tokens)
- **Controle de Versão:** Git & GitHub

---

## 🔐 Regras de Negócio e Perfis de Acesso

| Perfil | Permissões no Sistema |
| :--- | :--- |
| **Aluno / Participante** | Pode criar/entrar em uma equipe, gerenciar os membros da sua equipe e realizar/editar a submissão do projeto dentro do prazo. |
| **Avaliador / Banca** | Pode visualizar os projetos atribuídos à sua comissão, registrar avaliações e emitir comentários e feedbacks técnicos. |
| **Organizador** | Possui acesso total: gerencia usuários, equipes, prazos, bancas avaliadoras e gera o resultado final do evento. |

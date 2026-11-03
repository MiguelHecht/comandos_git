# 🚀 Guia Rápido de Comandos Git

Um guia simples e prático com os comandos mais utilizados no Git para o dia a dia de desenvolvimento.

---

## 📌 1. Configuração Inicial
Comandos usados para configurar sua identidade no Git pela primeira vez.

- **Definir nome de usuário:**
  ```bash
  git config --global user.name "Seu Nome"
  ```
- **Definir e-mail:**
  ```bash
  git config --global user.email "seu.email@exemplo.com"
  ```

---

## 📁 2. Criando ou Obtendo Repositórios

- **Iniciar um novo repositório na pasta atual:**
  ```bash
  git init
  ```
- **Baixar/Clonar um repositório existente do GitHub:**
  ```bash
  git clone URL_DO_REPOSITORIO
  ```

---

## 🔄 3. Fluxo de Trabalho Básico (O dia a dia)

- **Ver o status das alterações (arquivos modificados, novos ou deletados):**
  ```bash
  git status
  ```
- **Adicionar um arquivo específico para a área de preparação (staging):**
  ```bash
  git add nome-do-arquivo.extensao
  ```
- **Adicionar TODOS os arquivos modificados para staging:**
  ```bash
  git add .
  ```
- **Salvar as alterações adicionadas com uma mensagem explicativa:**
  ```bash
  git commit -m "Sua mensagem aqui"
  ```

---

## 🌐 4. Sincronizando com o Repositório Remoto (GitHub/GitLab)

- **Conectar seu repositório local a um servidor remoto:**
  ```bash
  git remote add origin URL_DO_REPOSITORIO
  ```
- **Enviar suas alterações salvas para o GitHub (pela primeira vez):**
  ```bash
  git push -u origin main
  ```
- **Enviar alterações para o GitHub (nos próximos envios):**
  ```bash
  git push
  ```
- **Baixar e atualizar seu código local com as novidades do GitHub:**
  ```bash
  git pull
  ```

---

## 🌿 5. Trabalhando com Branches (Ramificações)

- **Listar todas as branches existentes:**
  ```bash
  git branch
  ```
- **Criar uma nova branch:**
  ```bash
  git branch nome-da-branch
  ```
- **Mudar para uma branch existente:**
  ```bash
  git checkout nome-da-branch
  ```
- **Criar e mudar para a nova branch ao mesmo tempo:**
  ```bash
  git checkout -b nome-da-branch
  ```
- **Juntar (fundir) as alterações de outra branch na branch atual:**
  ```bash
  git merge nome-da-outra-branch
  ```

---

## 📜 6. Histórico e Desfazer Alterações

- **Ver o histórico de commits:**
  ```bash
  git log
  ```
- **Ver o histórico resumido (uma linha por commit):**
  ```bash
  git log --oneline
  ```
- **Descartar alterações locais em um arquivo (voltar ao último commit):**
  ```bash
  git checkout -- nome-do-arquivo
  ```

---

💡 **Dica rápida:** Para saber mais sobre qualquer comando, digite `git help <comando>` no terminal.

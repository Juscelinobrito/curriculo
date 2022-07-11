# curriculo
Usado na aula 02 de Git

## Para voltar pro branch principal
`git checkout main`

## Para atualizar o branch
`git pull origin nome-da-branch`
por exemplo, git pull origin main

## Criar um novo branch e seleciona ela
`git checkout -b nome-da-branch`

---
Agora você altera e/ou cria os arquivos conforme a solicitação do cliente e depois segue o processo abaixo
---

## 1º PASSO - Para adicionar os arquivos
`git add .` ou `git add arquivo.html`

## 2º PASSO - Para commitar/documentar o que foi alterado
`git commit -m "O que essa alteração faz?"`

## 3º PASSO - Para enviar para o git
`git push origin "nome-da-branch"` (main, develop, etc)
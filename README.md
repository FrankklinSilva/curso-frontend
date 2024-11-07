# Curso-Front-end
#### EBAC 

# GIT
## Conceitos de versionamento
  - Histórico
  - Controle de versão
  - Quem alterou
  - O quê alterou
  - Quando alterou
  - Todos os arquivos
  - Evolução contínua

Arquivo A | Versão 1 | Versão 2
Arquivo B | Versão 1 | Versão 2

## Instalação do Git
https://git.scm.com/

- Windows: https://git-scm.com/download/win
- Linux (apt-get): sudo apt-get install git
- Mac (brew): brew install git

## Criar conta no GitHub

## Clonar Projeto
git clone https://github.com/FrankklinSilva/curso-frontend.git

# Comandos básicos
  - git status (verifica os arquivos que foram modificados)
  - git add * (adiciona todos arquivos para subir)
  - git commit -m 'primeiro commit de código'
  - git push (enviar alterações para o repositorio)
  - git pull (puxar / trazer alterações do Github para sua maquina)

- Definindo configurações globais no git
  - git config --global user.nam e "Franklin Silva"
  - git config --global user.email "pdv.franksilva1@gmail.com"

  git config --get user.name (mostra nome do usuario atual no git)
  git config --get user.email (mostra email do usuario atual no git)

## Commits
Informação de alteração
- após testado todo seu código
- git add *
- git commit -m "mensagem"

## Gitflow
Fluxo do Git

### Branchs
são ramificações /versões paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop 
- DOD Definition of Done: critérios de aceite
- versionamento 1.0.0

PASSOS para criar uma branch developer:
1º use o comando: git checkout -b dev (com esse comando ele vai criar uma cópia da main para a branch dev)


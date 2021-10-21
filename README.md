# Curso Front-End
EBAC
# GIT
## Conceitos de versionamento
- Histórico
- Controle de versão
- Quem alterou
- O que alterou
- Quando alterou
- Todos os arquivos
- Evolução contínua

Arquivo A | Versão 1 | Versão 2
Arquivo B | Versão 1 | Versão 2

## Instando o Git
https://git-scm.com/

- Windows: https://git-scm.com/download/win
- Linux (apt-get): sudo apt-get install git
- Mac (brew): brew install git


## Criando conta no Github
## Clonar o projeto
git clone https://github.com/pedroruangd/front-end.git
## Commits
Informação de alteração
- Após testado todo seu código
- git add *
- git commit -m 'mensagem sem acentuacao'
- git push (enviar alterações para o repositório)
- git pull (puxar/trazer aterarações do Github para sua máquina)

## GitFLow
Fluxo do Git

### Branchs
São ramificações / versões paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop
- DOD Definition of Done: critérios de aceite
- versionamento: 1.0.13 (versão final | grande alteração | correções/bugs)

git checkout -b dev (cria uma branch nova)
git checkout dev (muda de branch)

### Merge
Mescla de branchs
Você pode precisar resolver conflitos manualmente

git merge main

### Pull Requests
Mescla de branchs no repositório
Permite code review
O repositório resolve os conflitos automaticamente

### Configura o Gitflow
git flow init
git flow feature start {nome-da-feature} 


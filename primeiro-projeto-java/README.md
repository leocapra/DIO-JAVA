# Curso  de Java Básico DIO

### Repositório para armazenar todo o conteúdo do curso de java básico da DIO.

Meu perfil

- [dio.me/user/leoccapra](https://web.dio.me/users/leoccapra/?tab=achievements)



# DIO projeto de estudo para GIT e GITHUB

Um projeto de desenvolvimento para a dominação de uma ferramenta necessária para um desenvolvedor. Armazenar os resumos sobre Git e GitHub do curso de versionamento de código com Git e GitHub da [Digital Innovation One](www.dio.me)

## 📚 Documentação 
-  [Documentação Git](https://git-scm.com/doc)
-  [Documentação GitHub](https://docs.github.com/pt)

## 🖥️ Resumos das Aulas
| Aulas | Resumos |
|-------|---------|
|Alterações no repositório local | [Resumos]() |

## Resumo comandos
- comandos de configuração
```
git config --global user.name "Leonardo"
//configurar nome de usuario

git config --global user.email "leocapra@gmail.com"
//configurar email de usuario

git config user.name
//exibir nome de usuario

git config user.email
//exibir email de usuario

git config init.defaultBranch
//exibe o nome padrão da Branch

git config --global init.defaultBranch main
//muda o nome da branch padrão para main

git config --global --list
//mostra a configuração global
```

- comandos de ação
```
git init
//começar um git na pasta

git status
//mostrar alteração

git add
//adicionar uma modificação

git add .
//adicionar todas as modificações

git ignore
//ignorar alguma pasta

git commit -m"<MSG>"
//comitar com o nome do versionamento

git log
//mostrar detalhes

git reflog
//mostra todos os detalhes de commits

mkdir pasta
//criar pastas

touch pasta/exemplo.md
//criar arquivo

touch pasta/.gitkeep
//mostrar pasta vazia no status

echo pasta/ > .gitignore
//criar arquivo (exemplo de ignore)

clear
//limpa a tela

git remote add origin <LINK-DO-REPOSITÓRIO>
//conectar o repositório

git branch -M main
//forçar a renomeação da branch para main (válido apenas para caso o nome da branch não seja main)

git pull
//puxa o arquivo alterado no repositório remoto

git push -u origin main
//manda para o repositório remoto as alterações do repositório local

git checkout -b teste
//trocar a branch main para uma branch de teste

git checkout main
//volta para a branch principal

git branch -v
//mostra o ultimo commit de cada branch

git merge teste
//mescla a branch de teste com a branch principal

git branch -d teste
//deleta a branch de teste

git branch
//mostra todas as branchs

```

- comandos de desfazer alteração no repositório local

```
rm -rf .git
//em caso de dar init na pasta errada

git restore README.md
//recupera a ultima modificação salva

git commit --amend -m"<NOVAMSG>"
//em caso de alteração da mensagem do versionamento

git commit --amend
//também funciona em caso de alteração de mensagem do versionamento

git reset --soft <ID>
//volta para um commit passado específico

git reset --mixed <ID> / git reset <ID>
//volta para um commit específico sem estar com os arquivos tracked

git reset pasta/README.md
//remove arquivo

git restore --staged pasta/README.md
//recupera arquivo removido
```

## 🔎 Referências 
- [Digital Innovation One](www.dio.me)
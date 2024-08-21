# Curso  de Java Básico DIO

# Leocapra
Olá, me chamo Leonardo Capra. Estou começando nesse mundo de desenvolvimento, e estou me esforçando muito para conseguir me desenvolver dentro do mercado de trabalho e ser concorrido pelas empresas. Criei gosto em aprender linguagens de programação, e tenho muito interesse em aprender mais sobre lógica de programação. Penso em coisas que podem valer para meu CV e o principal, penso em de fato saber por a mão na massa, mostrar o que eu sei.
## Conecte-se comigo
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leocapra/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/leocapra) [![Instagram](https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/leoccapra/?next=%2F) [![Gmail](https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:leoccapra@gmail.com)

## Habilidades

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)

![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

![Vscode](https://img.shields.io/badge/Vscode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

## GitHub Stats

![Top Langs](https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=leocapra&layout=compact&bg_color=000&border_color=30A3DC&title_color=E94D5F&text_color=FFF)

## Minhas Contribuições

[![GitHub Streak](https://streak-stats.demolab.com/?user=leocapra&theme=bear&background=000&border=30A3DC&dates=FFF)](https://git.io/streak-stats)
### Repositório para armazenar todo o conteúdo do curso de java básico da DIO.

Meu perfil

- [dio.me/user/leoccapra](https://web.dio.me/users/leoccapra/?tab=achievements)



# DIO projeto de estudo para GIT e GITHUB

Um projeto de desenvolvimento para a dominação de uma ferramenta necessária para um desenvolvedor. Armazenar os resumos sobre Git e GitHub do curso de versionamento de código com Git e GitHub da [Digital Innovation One](www.dio.me)

## 📚 Documentação 
-  [Documentação Git](https://git-scm.com/doc)
-  [Documentação GitHub](https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository)

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
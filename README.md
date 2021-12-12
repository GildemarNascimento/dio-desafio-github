# Comandos Báscicos do Git/GitHu

Alguns comando básicos em git.

###### Ajuda

```
git help
```

###### Ajuda para um comando específico

```
git help<comando> / [git help init]
```

###### Listar configurações do git

```
git config --list
```

###### Setar usuario

```
- git config --global user.name <nomeDoUsuario>
```

###### Setar email

```
- git config --global user.email <email>
```

###### Setar o editor 

```
- git config –globla core.editor<vim/nano/code>
```

###### Criar um repositório local

```
git init
```

###### Verificar o estado do repositório

```
git status
```

###### Adicionar arquivos

```
git add .	
```

###### Fazer commit

```
git commit -m "mensagem que descreve o commit"
```

###### Empurrar aquivos para repositorio remoto

```
git push origin master/main
```

###### Atualizar o repositorio local em relação ao remoto

```
git pull origin master
```

###### Verificar a branch atual

```
git branch 
```

###### Movimenta-se entre brenche

```
git git checkout [branch]
```

###### Criar uma nova brench

```
git git checkout [branch] -b 
```

###### Juntar dois repositorios

```
git marge [branche]
```

###### Renomeiar da branch estando dentro dela

```
git branch -m [nome]
```

###### Renomeiar branch estando em outra brench

```
git branch -m [antigo] [nova]
```

###### Deletar a branch

```
git branch -d
```

###### Criar uma stash, uma caixa temporaria

```
git stash save "cometarios descritivos referente as alterações"
```

###### Listar a stash em formato de array

```
git stash list 
```

###### Estourar ou recuperar o stash, retirar da caixinha

```
git stash pop
```

###### Limpa a stash

```
git stash clear
```

###### Listar o git (log)

```
git log 
```

###### Listar historico em uma única linha

```
git log --oneline 
```

###### Exibe historico de forma gráfica

```
git log --graph
```

###### Abrir interface grafica

```
gitk
```

###### Links

[Plataforma de visualização gráfica do git](https://git-school.github.io/visualizing-git/)

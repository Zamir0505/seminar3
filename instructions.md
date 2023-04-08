# **Git instructions**

![git logo](git.jpg)

***Git** is a very popular version control system*

## Git informations:

* # *Create new repository*

      git init

* # *Check repository status*

      git status

* # *Add working directory*

      git add "filename"   
      (without "")(also TAB to help)

* # *Committing changes and changes with adding a message.*


      git commit 
      git commit -m "message"

* # *Add working directory and committing changes with adding a message.*

      git commit -am "message"

* # *Changes list in the repository.(Between two positions)*

      git diff
      git diff hash1 hash2

* # *View history commits with changes.*
      git log
      git log --all
      git log --oneline
      git log --oneline --all

* # *Switching branches and uploading their contents to the working directory.*

      git checkout <hash> (moving to this hash)
      git checkout master (moving to last branch)

## Ветвления
Ветвления нужны для работы и изменения определенной части файла

## Просмотр существующих ветвлений
    git log --graph
    git log --oneline --graph
    git log --oneline --all --graph

## Просмотр существующих веток

    git branch

## Создание новой ветки

    git branch branch_name

## Удаление ветки

    git branch -d branch_name

## Удаление ветки без подстверждения (даже если нет слияния ветки)

    git branch -D branch_name
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
**Ветвления нужны для просмотра и изменения определенной части файла**.

# Просмотр ветвлений
    git log --graph
## Ветвления в списке коммитов
    git log --oneline --graph
## Ветвления в списке всех коммитов
    git log --oneline --all --graph

## Просмотр существующих веток

    git branch

## Создание новой ветки

    git branch branch_name

## Удаление ветки

    git branch -d branch_name

## Удаление ветки без подстверждения (даже если нет слияния ветки)

    git branch -D branch_name

## Cлияние двух веток

    git merge branch_name
    (та ветка, которая указывается, сливается с веткой текущей)

## Удаленные репозитории

Удаленные репозитории это версии нашего проекта в инете, где можно дать доступ определенным лицам для командной работы и вложений коллективных идей, а также принятия или не принятия их.

# Hello, world! #

## Начинаем знакомство с контролем версий

## Команды git



git init - инициализировать файл

git add имя файла - зафиксировать и добавить изменения
git commit - сохранить файл

git checkout №commita - вернуться к заданной версии файла

git log - посмотреть список сохранений

git log--oneline - список сохранений в укороченном виде

git diff - посмотреть отличие последнего сохраненного файла от текущей работы

Выводит список комитов в виде красивого дерева

```sh
git graph 
```

Краткое дерево комитов

```sh
git log --oneline --graph
```

# GitHub.com 
сервис в интернете для работы с удаленными репозиториями

## Команды Git для работы с GitHub

~~~sh
git push - вытолнуть на сервер информацию из локального репозитория
~~~

~~~sh
git pull - перетащить информацию с сервера на локальный репозиторий
~~~

~~~sh
git clone <ссылка> - соединяет репозиторий на сервере с локальным репозиторием
~~~


## Инструкция по работе с языком MarkDown

#Большой шрифт

##Средний шрифт

*Курсив

**текст **  полужирный текст

## Конфликты при слиянии: 
можно нужный вариант выбрать вручную либо из предложенных системой


Локальный конфликт

## Инструкция по созданию Pull requrst
1. Делаем форк интересующего нас репозитория.
2. Делаем git clone для нашей версии этого репозитория.
3. Создаем ветку с предлагаемыми изменениями.
4. Производим все изменения только в этой ветке.
5. Отправляем эти изменения на свой аккаунт (push)
6. В окне на GitHub появляется возможность отправить pull request.


## Инструкция по созданию Pull requrst
1. Делаем форк интересующего нас репозитория.
2. Делаем git clone для нашей версии этого репозитория.
3. Создаем ветку с предлагаемыми изменениями.
4. Производим все изменения только в этой ветке.
5. Отправляем эти изменения на свой аккаунт (push)
6. В окне на GitHub появляется возможность отправить pull request.
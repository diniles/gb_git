# Инструкция по работе с Git

## Установка Git и Visual Studio Code

* Установка Git для Windows, MAC, Linux: https://git-scm.com/downloads

* Установка VSCode для Windows, MAC, Linux: https://code.visualstudio.com/Download

При первом использовании Git необходимо представиться.  Для этого нужно ввести в терминале 2 команды:
```
git config --global user.name «yourname»
git config --global user.email youremail@example.com
```
## Подготовка репозитория

Создать новый каталог и в нём (или в текущем каталоге) запустить команду:

```
git init
```
## Working with commits

add file(s)

```
git add "filename"

git add .
```
send file to repository
```
git commit -m “message”
```
## Other commands

* ```git log``` – вывод на экран истории всех коммитов с их хеш-кодами (```reflog``` new command)

* ```git checkout``` – переход от одного коммита к другому

* ```git checkout master``` – вернуться к актуальному состоянию и продолжить работу

* ```git diff``` – увидеть разницу между текущим файлом и закоммиченным файлом


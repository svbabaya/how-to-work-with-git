## Инструкция по работе с Git
---
На компьютере должен быть установлен Git. Все команды выполняются в окне терминала (для Windows это Git Bush).
## 1 Работаем на локальном компьютере
1.1 Переходим в домашнюю директорию, создаем директорию проекта, например **project** и сразу переходим в эту директорию:
```
$ cd ~
$ mkdir project && cd project
```
1.2 Создаем файл проекта, например **text.txt** и добавляем в него строку "Some text information":
```
$ touch text.txt
$ echo "Some text information" > text.txt
```
1.3 Создаем репозиторий Git в текущей директории project
```
$ git init
```
1.4 Добавляем файл **text.txt** в список для сохранения его текущего состояния:
```
$ git add text.txt
```
1.5 Делаем коммит, то есть сохраняем текущее состояние всех файлов, добавленных перед этим в список и оставляем комментарий "Add file text.txt"
```
$ git commit -m "Add file text.txt"
```
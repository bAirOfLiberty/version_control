# Подсказка по гит (дополненная версия)
## Создание репозитория
01. Инициализация репозитория
```sh
git init
```
02. Выбор директории в Windows
```sh
cd ~/Desktop/*name*
```
03. Добавить файл
```sh
git add
```
04. Сохранение изменений с указанием сообщения в ковычках (на английском языке)
```sh
git commit -m "*сообщение*"
```
05. Журнал изменений
```sh
git log
```
06. Журнал изменений в кратком виде (только первые несколько цифр и сообщение)
```sh
git log --oneline
```
07. Перейти к версии ....
```sh
git checkout *version*
```
08. Отобразить разницу между текущей версией и закоммиченного файла, можно указать код версии 
```sh
git diff 
```
## Работаем с ветками
09. Создание новой ветки
```sh
git branch *new_name_of_branche*
```
10. Список веток в репозитори
```sh
git branch
```
11. Переключиться на эту ветку
```sh
git checkout *branch_name*
```
12. Сливаем ветки, команда вызывается оттуа куда мы хотим добавить изменения
```sh
git merge *branch-name*
```
13. Удаление ветки

```sh
git branch -d *name_of_branch*
```
14. Отображение всех ветвей
```sh
git log --graph
```
## Работа с удаленным репозиторием
15. Команда кронирования удаленного репозитория на компьютер
```sh
git clone https......
```
16. Скачать изменения с удаленного репозитория с merge с локальной версией
```sh
git pull
```
17. Отправить изменения локальной версии на удаленный репозиторий
```sh
git push
```
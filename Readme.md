![картинка не грузится](https://gibbonsfornevada.com/img/linux/git-repo-for-dotfiles-clone-to-homefolder.png)
#  **<font color = AF2591> Инструкция для работы с Git и удалёнными репозиториями** 

## Что такое Git?
**==Git==** - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *__==git init==__*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка **.git**)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *__==git add==__*. Чтобы использовать команду *__==git add==__* напишите **git add <имя файла>**

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *__==git status==__*. Для этого необходимо в папке с репозиторием написать **git status**, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *__==git commit==__*. Выполняется она так: **git commit -m "<сообщение к коммиту>**. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *__==git checkout==__*. Используется она в папке с пепозиторием следующим образом: **git checkout <номер коммита>**

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *__==git log==__*. Для этого достаточно выполнить команду **git log** в папке с репозиторием

## **Ветки в Git**

* ### Создание ветки

Для того, чтобы создать ветку, используется команда *__==git branch==__*. Делается это следующим образом в папке с репозиторием: **git branch <название новой ветки>**

* ### Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *__==git merge <name branch>==__*

* ### Удаление веток
**Для удаления ветки ввести команду** *__==git branch -d name branch==__*

 
![файл перемещен](chill.jpg)

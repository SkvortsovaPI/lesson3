# Инструкция по работе с git


## Команды git:

* **git init** - создаёт в текущем каталоге новый подкаталог с именем .git , содержащий все необходимые файлы репозитория — структуру Git репозитория
* **git add** -  добавляет содержимое рабочего каталога в индекс (staging area) для последующего коммита
* **git commit -m**  - данные, которые находятся в index'е переносятся в репозиторий и устанавливаются соответствующие ссылки на эти данные. gФлаг –m вносит описание изменений
* **git commit -am** - берем файлы, котоые были отслеживаемы в последний раз
* **git statusпше**  - показывает состояния файлов в рабочем каталоге и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе
* **git log** - перечисляет коммиты, сделанные в репозитории в обратном к хронологическому порядке — последние коммиты находятся вверху
* **git diff** - используется для вычисления разницы между любыми двумя Git деревьями
* **git checkout** - позволяет перемещаться между ветками, созданными командой git branch
* **.gitignore**  - позволяет исключать папки, которые нам не нужны
* **git reflog**  - чтобы убедиться, что коммит произошел
* **git branch** - создание новой ветки
* **git branch -d** - удалить ветку
* **git merge** - для объединения двух веток. Объединяет несколько последовательностей коммитов в общую историю
* **git log --graph** 
* **git remote add origin (link)** - просмотреть список настроенных удалённых репозиториев
* **git pull** - скопировать себе с гитхаба изменения
* **git push** - скопировать изменения со своего компа в git
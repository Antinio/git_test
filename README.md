План занятия:

1. Что такое Git
2. Установка Git
3. Начало работы
4. Инициализация проекта
5. Первые изменения
6. Коммит
7. gitignore
8. Работа с ветками
9. Совмещение веток
10. Работа с Github


https://git-scm.com/
Подробная документация https://git-scm.com/book/ru/v2

--------------------------------------------------------------------

Git - это система контроля версий, позволяющая эффективно управлять историей исходного кода.

Любые изменения которые ты вносишь в проект могут быть сохранены с помощью Git. Ты можешь вернуться к любым ранее сохраненным версиям.

Без Git пришлось бы создавать копии проекта, что было бы проблемой при увеличении объема кода в приложении.

На текущий момент Git — стандарт для разработки.

--------------------------------------------------------------------

Git и GitHub
Для начинающих может быть непонятна разница между этими терминами.

Git — система контроля версий. Технология, которую можно скачать на компьютер.

Github — сервис, который позволяет работать с твоими Git проектами. Это
называется репозитории. Помимо Github существуют другие сервисы (например
Bitbucket, GitLab).

--------------------------------------------------------------------

Как установить Git

Это бесплатная технология и скачать ее можно тут:
https://git-scm.com/downloads

Запускается через командную строку или терминал с команды git

--------------------------------------------------------------------

git --version

git --help

--------------------------------------------------------------------

Основные команды

git init

Позволяет проинициализировать репозиторий в текущей папке
--------------------------------------------------------------------

git status

Показывает текущий статус
--------------------------------------------------------------------

git add

Отслеживает изменения файлов

git add index.html — добавляет index.html
git add . — добавляет все файлы
--------------------------------------------------------------------

git commit

Сохраняет изменения в коммит

git commit -m 'commit message' — создает коммит с сообщением
--------------------------------------------------------------------

git branch

Работа с ветками в репозитории

git branch — показывает список веток
git branch branch-name — создает новую ветку branch-name
git branch -D branch-name — удаляет ветку branch-name
--------------------------------------------------------------------

git checkout

Переключается на другую ветку

git checkout branch-name — переключается на последний коммит в ветке
branch-name
git checkout -b branch-name — создает и переключается на ветку branch-name
--------------------------------------------------------------------

git merge

Совмещает текущую ветку с выбранной

git merge branch-name — совмещает текущую ветку с branch-name
--------------------------------------------------------------------

git config

Конфигурация и параметры git

git config --global user.name — Показывает имя пользователя
git config --global user.name 'new user' — Изменяет имя пользователя
git config --global user.email — Показывает email пользователя
git config --global user.email 'test@mail.ua' — Изменяет email пользователя
--------------------------------------------------------------------

git push

Заливает текущие локальные коммиты в удаленный репозиторий
--------------------------------------------------------------------

git pull

Забирает изменения с удаленного репозитория в локальный
--------------------------------------------------------------------

git clone

Клонирует проект с удаленного репозитория
--------------------------------------------------------------------

.gitignore 







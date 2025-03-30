# Создали my_first_repo
Инициализируем локальный репозиторий:
```sh
git init
```
Переименовать ветку GIT master в main:
```sh
git branch -M main
```
Задать удаленный репозиторий по умолчанию:
```sh
git remote add origin https://github.com/avil747/my_first_repo.git
```
Отобразить заданный удаленный репозиторий:
```sh
git remote show
```
Синхронизировать локальные изменения репо с внешним репозиторием:
```sh
git push -u origin main
```
Просмотр удаленных репозиториев на чтение (fetch) и записи (push):
```sh
git remote -v
```
Просмотр настроек удаленного репозитория (origin):
```sh
git remote show origin
```

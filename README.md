# Описание

Структура проекта выглядит примерно так:<br>
├── [api (backend)]<br>
├── [client (frontend)]<br>
├── docker<br>
└── остальные файлы докера (docker-compose, .dockerignore, aliases)

# Аллиасы

### Git Bash

В папке пользователя (C:\Users\ [Имя_Пользователя]\ ) можно создать файл .bash_profile и вставить алиасы... например:

```
alias dclogs='winpty docker-compose logs -f'
```

или указать путь до файла с алиасами

```
source путь/до/файла
```

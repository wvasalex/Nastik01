# Удаленные репозитории

Добавление удаленного репозитория
Чтобы добавить новый удаленный репозиторий, выполните команду git remote add в терминале в каталоге, в котором хранится репозиторий.

Команда git remote add принимает два аргумента:

имя удаленного репозитория, например, origin;
URL-адрес удаленного репозитория, например, https://github.com/user/repo.git.
Пример:

$ git remote add origin https://github.com/USER/REPO.git
# Set a new remote

$ git remote -v
# Verify new remote
> origin  https://github.com/USER/REPO.git (fetch)
> origin  https://github.com/USER/REPO.git (push)

## Базовые команды

+ git status - посмотреть изменения

+ git commit - оставить комментарий 

+ git iog - существующие версии файла и изменения

 # Конец ветки 4
# git-config

git config --global user.name “Сергей Баклагин”
git config --global user.email “Sergey2bn@mail.ru”

git config --list # посмотреть настройки

git config --global core.autocrlf true
git config --global core.quotepath off
git config --global core.safecrlf warn
git config --global init.defaultBranch main

git init # инициализация репозитория
git add . # добавить все файлы в track
git commit -m "описание" # сделать коммит
git status # показывает текущий статус
git diff # показывает текущие изменения
git diff --color-words # показывает более развернуто изменения
git checkout . # вернуться к последнему коммиту
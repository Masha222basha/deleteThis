# Команды в git
## Инициализация и конфигурация
- git init — инициализация нового репозитория
- git clone <url> — клонирование удалённого репозитория
- git config user.name "Имя" — установка имени автора
- git config user.email "email@example.com" — установка email автора
- git config --global core.editor "editor" — настройка редактора
- git config --list — показать все настройки


## Работа со статусом и историей
1. git status
   - показать состояние рабочей директории и индекса
2. git add <файл|папка>
   - добавить файл/папку в индекс
3. git add -A
   - добавить все изменения
4. git commit -m "сообщение"
   - создать коммит
5. git commit --amend -m "новое сообщение"
   - изменить последний коммит
6. git log
   - показать историю коммитов
7. git log --oneline --graph --decorate --all
   - компактный граф истории
8. git show <commit>
   - показать детали коммита
9. git blame <файл>
   - показать авторов строк файла

## Вопрос
#### Как отправить созданный локально тег на удалённый репозиторий?
- [ ] ***git push origin --all***
- [X] **git push origin <tagname>**
- [ ] *git push --tags-only*

## Таблица

| Команда | Описание | Пример |
|---|---|---|
| git init | Создать новый репозиторий | git init |
| git clone | Склонировать удалённый репозиторий | git clone URL |
| git add | Добавить файлы в индекс (staging) | git add файл |
| git commit | Зафиксировать изменения в истории | git commit -m "сообщение" |
| git status | Показать состояние рабочего дерева и индекса | git status |
| git log | Просмотреть историю коммитов | git log --oneline |
| git diff | Показать изменения между состояниями | git diff HEAD |
| git branch | Управление ветками | git branch, git branch имя |
| git checkout | Переключиться на ветку/коммит | git checkout ветка |
| git merge | Слить одну ветку в текущую | git merge ветка |
| git rebase | Перенести коммиты на другой базовый | git rebase ветка |
| git stash | Временно сохранить изменения | git stash, git stash pop |
| git remote | Управление удалёнными репозиториями | git remote add origin URL |
| git push | Отправить коммиты/теги на удалённый | git push origin ветка |
| git pull | Забрать и слить изменения с удалённого | git pull |

# Котик
<p align="center">
  <img width="400" height="250" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ29ppdzqXN6nP-msl1kg7C0Ry-YgR49gnMEQ&s">
</p>

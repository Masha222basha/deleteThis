# Инициализация и конфигурация
- git init — инициализация нового репозитория
- git clone <url> — клонирование удалённого репозитория
- git config user.name "Имя" — установка имени автора
- git config user.email "email@example.com" — установка email автора
- git config --global core.editor "editor" — настройка редактора
- git config --list — показать все настройки


# Работа со статусом и историей
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

# Вопрос
#### Как отправить созданный локально тег на удалённый репозиторий?
- [ ] ***git push origin --all***
- [X] **git push origin <tagname>**
- [ ] *git push --tags-only*

<p align="center">
  <img width="400" height="250" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ29ppdzqXN6nP-msl1kg7C0Ry-YgR49gnMEQ&s">
</p>

# git-helping-out-a-friend

# Основы работы с Git

## 🔧 Инициализация проекта

```bash
git init


git add filename     # добавить конкретный файл
git add .            # добавить все изменения в текущей папке


git commit -m "Краткое описание изменений"


git status           # показывает текущие изменения


git log              # выводит список всех коммитов

Связь с удалённым репозиторием
git remote add origin https://github.com/username/repo.git

git push -u origin main      # первый пуш
git push                     # следующие пуши


git clone https://github.com/username/repo.git


git pull
```
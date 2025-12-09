
# Основные команды Git & GitHub
## Содержание
- [Настройка Git](https://github.com/avted/git-101#настройка-git)
- [Создание репозитория](https://github.com/avted/git-101#создание-репозитория)
- [Добавление изменений и коммит](https://github.com/avted/git-101#добавление-изменений-и-коммит)
- [Работа с ветками](https://github.com/avted/git-101#работа-с-ветками)
- [Слияние веток](https://github.com/avted/git-101#слияние-веток)

## Настройка Git

Установить имя пользователя
```
git config --global user.name "NAME"
```

Установить email
```
git config --global user.email "YOUR@EMAIL.COM"
```

Проверить настройки
```
git config --list
```

## Создание репозитория

Инициализировать новый репозиторий 
```
git init 
```

Клонировать существующий репозиторий с GitHub 
``` 
git clone https://github.com/USERNAME/repository.git
``` 

## Добавление изменений и коммит

 Добавить конкретный файл 
``` 
git add filename.txt 
``` 

Добавить все файлы 
``` 
git add .
```

Создать коммит с сообщением
```
git commit -m "Описание изменений"
```

Добавить файлы и закоммитить с сообщением
```
git add . && git commit -m "Описание изменений"
```

## Работа с ветками

Показать все ветки
```
git branch
```

Создать новую ветку
```
git branch feature
```

Переключиться на ветку
```
git checkout feature
```

Создать и сразу переключиться
```
git checkout -b feature-name
```

## Слияние веток

Переключиться на главную ветку
```
git checkout main
```

Слить другую ветку в текущую
```
git merge feature
```

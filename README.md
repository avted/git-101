
# Основные команды Git & GitHub
## Содержание
- [Настройка Git](https://github.com/avted/git-101#%D0%9D%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0%20Git)
- [Создание репозитория](https://github.com/avted/%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D1%8F)
- [Добавление изменений и коммит](https://github.com/avted/%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%B8%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B8%D1%82)
- [Работа с ветками](https://github.com/avted/%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%81%20%D0%B2%D0%B5%D1%82%D0%BA%D0%B0%D0%BC%D0%B8)
- [Слияние веток](https://github.com/avted/%D0%A1%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D0%B5%20%D0%B2%D0%B5%D1%82%D0%BE%D0%BA)

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

# Урок 1
## Работа с системой контроля версий
1. Инициализация пустого репозитория
```
git init
```
2. Изменение пользовательской конфигурации
```
git config --global user.name "Val Tuchkevich"
git config --global user.email "valtu4a@gmail.com"
```

3. Создание файла исключений

```gitignore
# Файлы
desktop.ini
Thumbs.db
.DS_Store
# Директория
.idea/
node_modules/
log/*
!/log/.htaccess
```

4. Добавление файлов в индексируемые

```
git add "имя_файла"
```
Индексируем все файлы в проекте (за исключением тех, что описаны в файле исключений)
```
git add .
```


5. Убрать файл из индексируемых
```
git rm -cached  "имя_файла"
```

6. Фиксация изменений
```
git commit -m "сообщение"
```

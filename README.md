Title: Генерация статических сайтов из Markdown с помощью Pelican
Date: 2021-01-26 12:00


## Установка Pelican:
```
python -m pip install "pelican[markdown]" 
```

## Настройка
Настройка осуществляется командой:
```
pelican-quickstart
```
Далее отвечаем на вопросы.
После этого в текущей папке создатутся папки (output, content) и файлы конфигурации


## Генерация сайта

Кладём наш markdown файл в папку content и вводим команду 
```
pelican
```

В папке ./output появится index.html

PROFIT


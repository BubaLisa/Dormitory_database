# Dormitory_database

В файле Dormitory_database.zip хранятся все запросы и backup Базы данных для ее запуска
Требования к запуску:
- Установлен Postgresql и pgAdmin
- Скачан zip-архив бд

Инструкция по запуску

1. Запустить pgAdmin
2. В разделе Databases создать новую базу данных: ПКМ на Databases -> Create -> Database -> В поле Database ввести название БД(например Dormitory) -> Save
3. Нажать ПКМ на созданную базу данных -> Restore... -> В поле Format выбрать Custom or tar -> в поле Filename нажать на значок папки и найти файл Dormitory_backup1.backup в скачанном архиве -> Restore

Поздравляем, вы запустили базу данных Dormitory!

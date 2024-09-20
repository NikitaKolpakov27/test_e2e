# E2E UI

## *В данном проекте представлен автоматический тест на Python + Selenium, проверяющий процесс от авторизации на сайте до завершения покупки.*


## Инструкция по запуску
Ниже приведенные шаги выполняются друг за другом.

## 1. Клонирование репозитория и переход в папку с тестом:
```
   git clone https://github.com/NikitaKolpakov27/test_e2e.git
   cd test_e2e
```

## 2. Установка зависимостей:
```
pip install -r requirements.txt
```

## 3. Создание файла .env:
Файл создается в папке с тестом. В файле должны быть указаны все данные, касаемо задачи.
```
USER_NAME=site_user_name
PASSWORD=site_password
FIRST_NAME=first_name_for_order
LAST_NAME=last_name_for_order
ZIP_CODE=zip_code
```

## 4. Запуск скрипта (в папке с тестом):
```
test_e2e.py
```
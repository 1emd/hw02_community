# backend_community_homework

### Описание:
Второй проект для блога-платформы, «Социальная сеть блогеров». Было создано и зарегистрировано приложение под названием "Posts". В приложении была подключена база данных. На главной странице приложения выводится информация о последних десяти записях. В административной зоне приложения доступны функции управления объектами модели "Post": можно создавать новые записи, а также редактировать или удалять существующие.
Пользователи имеют возможность перейти на страницу любого сообщества, где отображаются последние десять публикаций, относящихся к этой группе.

### Инструкция по установке:

1. Клонируйте репозиторий и перейдите в него в командной строке:
  ```
  git clone git@github.com:1emd/hw02_community.git
  cd hw02_community
  ```
2. Создайте и активируйте виртуальное окружение:
  ```
  python3 -m venv venv
  ```
- Linux/macOS:

  ```
  source venv/bin/activate
  ```

- Windows:
  ```
  source env/scripts/activate
  ```

3. Установите зависимости из файла requirements.txt:
  ```
  pip install -r requirements.txt
  ```

4. Выполните миграции:
  ```
  python3 manage.py migrate
  ```

5. Запустите проект:
  ```
  python3 manage.py runserver
  ```

### Автор:
[Кирилл Хорошилов](https://github.com/1emd)



[![CI](https://github.com/yandex-praktikum/hw02_community/actions/workflows/python-app.yml/badge.svg?branch=master)](https://github.com/yandex-praktikum/hw02_community/actions/workflows/python-app.yml)

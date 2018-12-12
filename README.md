# Интенсив по технической документации

## Сборка сайта

Через Poetry:

1.  Установите Poetry:

    ```shell
    curl -sSL https://raw.githubusercontent.com/sdispater/poetry/master/get-poetry.py | python
    ```

2.  Клонируйте репку:

    ```shell
    git clone git@bitbucket.org:moigagoo/techdocsintensive.git
    ```

3.  Установите зависимости:

    ```shell
    cd techdocsintensive
    poetry install
    ```

4.  Соберите сайт:

    ```shell
    poetry run mkdocs serve
    ```

5.  Откройте доки в браузере по адресу http://localhost:8000.

Или через Докер:

1.  Скачайте образ:

    ```shell
    docker pull squidfunk/mkdocs-material
    ```

2.  Соберите сайт:

    ```shell
    docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
    ```

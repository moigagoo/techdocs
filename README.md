# Интенсив по технической документации

## Сборка

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

4.  Соберите доки:

    ```shell
    poetry run mkdocs serve
    ```

5.  Откройте доки в браузере по адресу http://localhost:8000.
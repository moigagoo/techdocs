[![Build Status](https://travis-ci.org/moigagoo/techdocs.svg?branch=develop)](https://travis-ci.org/moigagoo/techdocs)

# Техническая документация для инженеров. Двухдневный интенсив

Актуальная версия: https://moigagoo.github.io/techdocs


## Локальная сборка

### Docker

1.  `docker pull squidfunk/mkdocs-material`

2.  `docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material`


### Poetry

0.  `curl -sSL https://raw.githubusercontent.com/sdispater/poetry/master/get-poetry.py | python`

1.  `poetry install`

2.  `poetry run mkdocs serve`

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/MrSunstrike/kittygram_final.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

[![CI](https://github.com/MrSunstrike/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/MrSunstrike/kittygram_final/actions/workflows/main.yml)

## Авторы

- [Никитин Михаил](https://github.com/MrSunstrike) - автор
- [Кубарев Дмитрий](https://github.com/dkuba) - ревьюер

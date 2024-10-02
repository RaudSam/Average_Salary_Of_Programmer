# Сравниваем вакансии программистов

Скрипт анализирует вакансии программистов на сайтах **_HeadHunter_** и **_SuperJob_** и выводит их статистику в виде таблицы.

### Как установить

Для запуска кода понадобится ключ к API `SuperJob`. Для этого зарегистрируйтесь на сайте: <https://api.superjob.ru/>.

Создайте в корне проекта, файл ``.env`` Пропишите в нем:

```
SJ_KEY='Ваш ключ'
```

Python3 должен быть уже установлен. Затем используйте pip (или pip3, есть конфликт с Python2) для установки зависимостей:

```
pip install -r requirements.txt
```

### Применение

Для получения таблицы с данными запустите код из консольной утилиты:

```
python main.py
```

Программа выдаст 2 таблицы со статистикой по языкам программирования c сайтов:

```
+SuperJob / +HeadHunter Moscow-------------------------------------------------------
| Язык программирования | Вакансий найдено | Вакансий обработано | Средняя зарплата |
+-----------------------+------------------+---------------------+------------------+
| Python                | 0000             | 000                 | 000000           |
| Java                  | 0000             | 000                 | 000000           |
| JavaScript            | 0000             | 000                 | 000000           |
| C++                   | 0000             | 000                 | 000000           |
| C#                    | 0000             | 000                 | 000000           |
| C                     | 0000             | 000                 | 000000           |
| PHP                   | 0000             | 000                 | 000000           |
| Ruby                  | 0000             | 000                 | 000000           |
+-----------------------+------------------+---------------------+------------------+

```

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).

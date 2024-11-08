# Домашнее задание к занятию «2.4. Потоки RxJS»

### Подготовьте рабочую среду для дальнейшей работы.

#### Клонируйте проект из репозитория.

Разверните стартовый проект у себя на локальной машине.

**Выполните задания.**

**Задание 1.**

Сделайте обращение к GitHub API, как в примерах на лекции, с использованием RxJS. 
Пример реализации этого запроса предоставлен в стартовом проекте.
```sh
https://api.github.com/search/repositories?q=${текст запроса}
```
:white_check_mark:
Ищет все репозитории про тетрисы и выводит hub=12312 в консоль
```http://localhost:3000/rxjs/repositories?text=tetris+language:assembly&hub=12312```

**Задание 2.**

С использованием RxJS сделайте запросы к любому общедоступному API (например, аналогичное с GitHub API [GitLab](https://docs.gitlab.com/ee/api/README.html#basic-usage)).
```sh
https://gitlab.com/api/v4/projects?search=${текст запроса}
```

:white_check_mark:
Получает погоду в городе Перми
```http://localhost:3000/weather?place=Perm```
# Домашнее задание к занятию "`Домашнее задание к занятию «Что такое DevOps. СI/СD»`" - `Бакулев Евгений`

### Задание 1
### Что нужно сделать:

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins golang.
3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Решение 1

![Скрин](https://github.com/garrkiss/8-02-hw/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2014.04.24_17.22.10.png)

![Скрин](https://github.com/garrkiss/8-02-hw/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2014.04.24_17.22.18.png)


![Скрин](https://github.com/garrkiss/8-02-hw/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2014.04.24_17.20.15.png)

![Скрин](https://github.com/garrkiss/8-02-hw/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2014.04.24_17.20.27.png)

![Скрин](https://github.com/garrkiss/8-02-hw/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2014.04.24_17.21.10.png)

### Задание 2
### Что нужно сделать:

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.


### Решение 2

![Скрин](https://github.com/garrkiss/8-02-hw/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2014.04.24_17.34.06.png)

![Скрин](https://github.com/garrkiss/8-02-hw/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2014.04.24_17.33.50.png)


### Задание 3
### Что нужно сделать:

1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Решение 3

![Скрин](https://github.com/garrkiss/8-02-hw/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2014.04.24_17.42.05.png)

![Скрин](https://github.com/garrkiss/8-02-hw/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2014.04.24_17.41.51.png)


![Скрин](https://github.com/garrkiss/8-02-hw/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2014.04.24_17.41.35.png)
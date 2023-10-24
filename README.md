
# Домашнее задание к занятию **Что такое DevOps. СI/СD - Стригунов Олег**
### Задание 1
1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins golang.
3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
### Ответ 1 
![Скрин 1](https://github.com/olegstrigunov/sdvps-materials/blob/master/pip1.png)
![Скрин 2](https://github.com/olegstrigunov/sdvps-materials/blob/main/1.png)
![Скрин 3](https://github.com/olegstrigunov/sdvps-materials/blob/main/Снимок%20экрана%201.png)
-------
### Задание 2
1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.
### Ответ 2 
![Скрин 1](https://github.com/olegstrigunov/sdvps-materials/blob/master/pip2.png)
![Скрин 2](https://github.com/olegstrigunov/sdvps-materials/blob/main/2.png)
![Скрин 3](https://github.com/olegstrigunov/sdvps-materials/blob/main/3.png)
------
### Задание 3 и Задание 4
1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.
5*. Придумайте способ версионировать приложение, чтобы каждый следующий запуск сборки присваивал имени файла новую версию. Таким образом, в репозитории Nexus будет храниться история релизов.
### Ответе 3 и 4 
![Скрин 1](https://github.com/olegstrigunov/sdvps-materials/blob/master/pip3.png)
![Скрин 2](https://github.com/olegstrigunov/sdvps-materials/blob/master/3.png)
![Скрин 3](https://github.com/olegstrigunov/sdvps-materials/blob/master/4.png)

## Дополнительные материалы для выполнения домашних заданий из блока "Введение в DevOps"


- [Дополнительный материал для занятия "8.2. Что такое DevOps. СI/СD"](CICD/8.2-hw.md)

- [Дополнительный материал для занятия "8.3. GitLab"](https://github.com/netology-code/sdvps-materials/tree/main/gitlab)


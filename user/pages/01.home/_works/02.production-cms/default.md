---
title: Production-cms
---

Переписал с нуля свой старый проект на современный фреймворк. В проекте организованна работа с программами для станков с ЧПУ и пользователями работающими с ними. Загрузка в базу, редактирование, просмотр и удаление программ. Поиск осуществляется по нескольким параметрам или по оному любому, если другие не отмечены. Так же добавлена возможность для типов пользователя "мастер" - просмотр и управления заданиями. Сущности: Программы, станки, пользователи, материал, типы материалов, смены, задания. Проект выполнен на laravel 9. На фронте blade+tailwind код . Для тестового доступа можно зайти под 9999/12345678
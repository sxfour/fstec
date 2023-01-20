# Fstec finder on csv & postgresql

1. [Vers. WITH POSTGRESQL]
- Обновлённая версия, так как база уязвимостей имеет более 40 тысяч записей, то решил, использовать PostgreSQL
![изображение](https://user-images.githubusercontent.com/112577182/213695142-2b35ee6d-df69-449b-8936-a056ae6b6d89.png)


Для взаимодействия с базой данных, можно импортировать готовую из этого репозитория, либо создать самим.
 
 - Вариант 1 create own.
Создание и настройка базы проводились на Windows 10 x64, с помощью pgAdmin, PostgreSQL 15.
Дополню позже.


- Вариант 2 import backup.
Импортируем готовый backup базы

![изображение](https://user-images.githubusercontent.com/112577182/213687761-3d16d62b-8c86-47d6-8b6b-354eb08c5e3e.png)






2. [Vers. WITHOUT SQL DATABASE]

- Поиск уязвимостей по csv данным fstec, используя ключевое слово для поиска, например CVE уязвимости

![fstec1](https://user-images.githubusercontent.com/112577182/211744232-2318449c-4877-4e3f-bd71-4159cc4ca29c.PNG)

- Результат отражается с помощью rich tables в консоль

![Снимок2](https://user-images.githubusercontent.com/112577182/211798353-8883df39-15b6-47fc-a522-9457ae6a8dbc.PNG)

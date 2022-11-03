Данное консольное приложение было написано с целью продемонстрировать как можно самостоятельно реализовать БД и весь её функционал для предметной области "Армия", структура классов которой показана ниже.

![image](https://user-images.githubusercontent.com/80580481/199728759-11b9ee6e-192e-4d44-b00f-e41f7ef2bae4.png)
Сначала нужно самостоятельно инициализировать БД, а затем уже выполнять с ней какие-либо действия. Пример исходных данных для инициализации, в качестве примера описан один военнослужащий(мы пишем лишь данные, опуская те текстовые сообщения, прочитав который нужно их вводить, т.е. весь поток вывода программы):
pilot 31.01.2001 m russian Sharipov Andrey Sergeevich major 10 765
После инициализации БД подобными элементами, можно приступать к работе с ней(любая из функций 3-6, а также её подфункции), например, функция 5(поиск) и её подфункция 4(содержит ...):
5
pilot
gender
4
m
Для заданной БД и указанного выше запроса в качестве вывода будет предоставленна вся информация по указанному выше единственному человеку в БД, т.к. его гендер совпадает с искомым.

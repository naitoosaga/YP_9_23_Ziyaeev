/*
 Конспект на тему функции
функции и параметры:

При разработке большинства приложений их разделяют на функциональные модули в C# приложение состоит из классов которые содержат

именнованные блоки кода называемые методами

Метод(функции - это часть класса, которая может осуществлять действие или вычислять значение)

Мспользование методов, метод - это набор операторов которые выполняются вместе, для создания метода необходимо задать его имя

Определить список параметров и тело метода. Для вызова метода другого класса необходимо, чтобы он был объявлен как паблик,

Вызов осуществляется по имени класса и метода. Eсли метод не void, то необходимо вернуть значение соответствующего типа

Оператор return останавливает выполнение метода, и передает управление вызвавщему данные методы оператору.

Каждый метод имеет набор своих локальных переменных, они видны только в нем и при завершении работы метода - уничтожаются

Для того чтобы переменные были видны в нескольких методах класса, нужно обьявить их полями не метода, но внутри класса 

Для не void методов необходимо возвращать значение каждой "путь выполнения" метода должен заканчиваться оператором return

Для void-методов оператор return необязательный

Использование параметров

Параметры позволяют передавать информацию из одного метода в другой, при объявлении метода можно задать список его параметров, 

Eсли список пустой, то это значит что метод не имеет параметров

В C# Существует 3 варианта передачи параметров: 

1. По значению
(изменение значения параметра в методе не влияет на значение вызвавшем методе)

2. По ссылке
(необходимо указывать ключевое слово ref )

3. Входные параметры
(ключевое слово)

до вызова метода необходим обязательно инициализировать переменные

в С# позволяет использовать механизм передачи списка параметров изменяемой длины, для это используется ключевое слово - params

Модификаторы доступа - это ключевые слова, которые задают обьявленный уровень доступности члена или типа

Семь уровней специальных возможностей модификаторов доступа
1.public
2.protected
3.internal
4.protected internal
5.private
6.private protected
7.file

Модификатор abstract указывает что изменяемый элемент имеет отсутствующую или неполную реализацию

модификатор async позволяет указать что метод является синхронным 

Модификатор static можно добавить в локальную функцию, используется для объявления статического члена, принадлежащего собственному

типу а не конкретному 
*/

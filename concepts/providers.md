Service Providers являются центральным элементом начальной загрузки всех приложений Laravel. 
Они выполняют необходимую инициализацию, регистрацию и настройку сервисов в приложении Laravel.

Все поставщики услуг расширяют класс `Illuminate\Support\ServiceProvider`. 
Каждый поставщик услуг имеет свой метод `register()`, 
в котором можно зарегистрировать свой сервис или добавить новые функции к уже существующим. 
Также у каждого поставщика услуг есть метод `boot()`, 
который вызывается после регистрации всех поставщиков
и позволяет произвести дополнительную настройку и инициализацию сервисов.

[//]: # "materials"

- [Документация](https://laravel.com/docs/10.x/providers)
- [Курс интернет магазин на Laravel. Урок 1. Подготовка и настройка проекта](https://www.youtube.com/watch?v=cD247LTT9Dw&list=PLTucyHptHtTkveNJf17ypoZoG3pdnvs6v&index=2&t=659s)

[//]: # "/materials"
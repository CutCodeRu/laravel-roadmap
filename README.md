# Laravel Roadmap от CutCode

1. ИНСТРУМЕНТЫ РАЗРАБОТКИ
    1. [PHPDoc](tools/phpdoc.md)
    2. [Git](tools/git.md)
    3. [Конвенция наименований в Laravel](tools/conventions.md)
    4. [Code Style](tools/codestyle.md)
    5. [PhpStorm](tools/phpstorm.md)
    6. [Visual Studio Code](tools/vscode.md)
2. [УСТАНОВКА](installation/index.md)
    1. [Установка через Composer](installation/composer.md)
    2. [Установка через Docker](installation/composer.md)
3. [МАРШРУТИЗАЦИЯ (ROUTING)](routing/index.md)
    1. [Основы (Basic Routing)](routing/basic-routing.md)
    2. [Параметры маршрутов (Route Parameters)](routing/route-parameters.md)
    3. [Именованные маршруты (Name router)](routing/named-routes.md)
    4. [Привязка модели (Route model binding)](routing/route-model-binding.md)
    5. [Группы маршрутов (Route group)](routing/route-groups.md)
    6. [Резервные маршруты (Fallback Routes)](routing/fallback-routes.md)
    7. [Кеширование маршрутов (Caching)](routing/route-caching.md)
    8. [Подмена методов форм (Form Method Spoofing)](routing/form-method-spoofing.md)
    9. [Ограничение трафика (Rate limiting)](routing/rate-limiting.md)
    10. [Cross-Origin Resource Sharing CORS](routing/cors.md)
4. MIDDLEWARE
    1. [Middleware](middleware/middleware.md)
5. [КОНТРОЛЛЕРЫ](controllers/index.md)
    1. [Базовые контроллеры](controllers/basic-controllers.md)
    2. [Контроллеры ресурсов (Resource controller)](controllers/resource-controllers.md)
    3. [Вложенные ресурсы (Nested Resources)](controllers/nested-resources.md)
    4. [Внедрение зависимостей (Dependency Injection)](controllers/dependency-injection.md)
    5. [Одноэлементные контроллеры (Single action controller)](controllers/single-action-controllers.md)
    6. [Неглубокая вложенность Shallow nesting)](controllers/shallow-nesting.md)
6. VIEWS
    1. [Шаблоны](views/basic-views.md)
    2. [View Composers](views/view-composers.md)
7. [BLADE](blade/index.md)
    1. [Отображение данных (Displaying Data)](blade/displaying-data.md)
    2. [Blade директивы (Blade Directives))](blade/blade-directives.md)
    3. [Макеты (Layout)](blade/layouts.md)
    4. [Компоненты (Components)](blade/components.md)
    5. [Формы (Forms)](blade/forms.md)
    6. [Subview](blade/including-subviews.md)
    7. [Service Injection](blade/service-injection.md)
    8. [Расширение Blade (Extending Blade)](blade/extending-blade.md)
8. FRONTEND
    1. [Bundling Assets](frontend/bundling-assets.md)
    2. [Livewire](frontend/livewire.md)
    3. [Inertia](frontend/inertia.md)
    4. [Vue](frontend/vue.md)
    5. [React](frontend/react.md)
    6. [Splade](frontend/splade.md)
9. [БАЗА ДАННЫХ](database/index.md)
    1. [Конфигурация (Configuration)](database/configuration.md)
    2. [Запросы к базе данных (SQL Queries)](database/running-queries.md)
    3. [Конструктор запросов (Query builder)](database/queries.md)
    4. [Миграции (Migrations)](database/migrations.md)
    5. [Seeding](database/seeding.md)
10. [ELOQUENT](eloquent/index.md)
    1. [Модели (Models)](eloquent/eloquent.md)
    2. [Фабрики (Factories)](eloquent/eloquent-factories.md)
    3. [Коллекции (Collections)](eloquent/eloquent-collections.md)
    4. [Отношения в Laravel (Defining Relationships)](eloquent/defining-relationships.md)
    5. [Отношение многие ко многим (Many To Many Relationships)](eloquent/many-to-many.md)
    6. [Область запросов (Query scopes)](eloquent/query-scopes.md)
    7. [Accessors / Mutators](eloquent/accessors-and-mutators.md)
    8. [Casting](eloquent/attribute-casting.md)
    9. [Eager loading](eloquent/eager-loading.md)
    10. [Полиморфные отношения (Polymorphic relation)](eloquent/polymorphic-relationships.md)
    11. [Подзапросы (Subqueries)](eloquent/advanced-subqueries.md)
    12. [Model events](eloquent/events.md)
    13. [API resource](eloquent/eloquent-resources.md)
    14. [Курсорная пагинация](eloquent/cursor-paginator.md)
11. [ОБРАБОТКА ОШИБОК](errors/index.md)
    1. [Using Exception in try...catch](errors/exception-handler.md)
    2. [Http Exception, Custom error page](errors/http-exceptions.md)
    3. [Customizing Renderable & Reporting Exception](errors/reporting-exceptions.md)
    4. [Global contextual data](errors/global-log-context.md)
12. [REQUEST](requests/index.md)
    1. [Получение входных данных (Retrieving Input)](requests/input.md)
    2. [Извлечение загруженных файлов (Retrieving Uploaded Files)](requests/files.md)
    3. [Методы запроса (Request methods)](requests/retrieving-request-url.md)
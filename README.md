## Генерация приложения

Пререквизиты:

- [npm](https://github.com/gusenov/auto-soft-install/blob/master/install/npm.sh)
- [Sencha Cmd](https://github.com/gusenov/auto-soft-install/blob/master/install/sencha-cmd.sh)

Команда:

```bash
$ npm run-script generate-my-app
```

## Краткий обзор структуры приложения

- [Фреймворк Ext JS](myapp/ext)

- [Главный класс приложения](myapp/app/Application.js)

- [Модель](myapp/app/model)

- [Уровень доступа к хранилищу данных](myapp/app/store)

- Вид

  - [Классический десктопный форм-фактор](myapp/classic)

    - [Представления](myapp/classic/src)

      - [Главное представление](myapp/classic/src/view/main/Main.js)

    - [Стили](myapp/classic/sass)

  - [Современный мобильный форм-фактор](myapp/modern)

    - [Представления](myapp/modern/src)

      - [Главное представление](myapp/modern/src/view/main/Main.js)

    - [Стили](myapp/modern/sass)

  - [Общие стили](myapp/sass)

- Модель вида (ViewModel)

  - [Главное представление](myapp/app/view/main/MainModel.js)
  
- Контроллер

  - [Главное представление](myapp/app/view/main/MainController.js)

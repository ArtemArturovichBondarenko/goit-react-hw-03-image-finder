# Webpack starter kit

[Живая страница](https://luxplanjay.github.io/webpack-starter-kit/) после деплоя
через `npm run deploy`.

## Использование

- Скачать репо как архив
- Переименовать папку под свой проект
- В консоли перейти в корень проекта
- Выполнить команду `npm install`
- Ждать пока установятся все зависимости

## Скрипты

- `npm start` - запускает режим разработки с дев-сервером.
- `npm run build` - запускает режим сборки в прод, создастся папка `build`.
- `npm run deploy` - запускает сборку в прод, после чего деплоит проект на
  GitHub Pages в репозиторий из свойства `homepage` в `package.json`.
  Автоматически создает ветку `gh-pages` в репозитории. Значение `homepage`
  необходимо подменить вручную на свой репозиторий.

## Папки и файлы

- `src` - тут лежат исходники.
- `src/index.html` - шаблон под html-файл, можно редактировать. В продакшене
  сюда автоматически добаввятся теги `link` и `script`.
- `src/index.js` - точка входа в приложение, сюда импортируем все остальное.
- `build` - автоматически создастся в продакшене, тут будут готовые файлы.

## Баги и улучшения

Если нашли баг открывайте `issue`, обсудим, если пофиксили открывайте
`pull request`.

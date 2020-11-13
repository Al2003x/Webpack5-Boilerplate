# Webpack 5 Boilerplate

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) ![David](https://img.shields.io/david/dev/taniarascia/webpack-boilerplate)

Sensible Webpack 5 boilerplate using Babel, PostCSS and Sass with a hot dev server and an optimized production build.

Масштабируемый шаблон настроек Webpack 5, включающий Babel и PostCSS, сервер для разработки и оптимизированную сборку для продакшна.

## Installation / Установка

```
git clone git@github.com:taniarascia/webpack-boilerplate
cd webpack-boilerplate
npm i / yarn
```

## Usage / Использование

### Development server / Сервер для разработки

```bash
npm start / yarn start
```

You can view the development server at `localhost:8080`.

Сервер запускается по адресу `localhost:8080`

### Production build / Сборка для продакшна

```bash
npm run build / yarn build
```

> Note: Install [http-server](https://www.npmjs.com/package/http-server) globally to deploy a simple server.

> Примечание: установите [http-server](https://www.npmjs.com/package/http-server) глобально для запуска простого сервера.

```bash
npm i -g http-server / yarn global add http-server
```

You can view the deploy by creating a server in `dist`.

Вы можете увидеть результат сборки, создав сервер в `dist`

```bash
cd dist && http-server
```

## Author / Автор

- [Igor Agapov](https://javascript-practice.ru)

## License / Лицензия

This project is open source and available under the [MIT License](LICENSE).

Проект является открытым и доступен под [MIT License](ЛИЦЕНЗИЯ).
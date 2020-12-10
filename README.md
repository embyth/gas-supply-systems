# :cyclone: Розрахунок системи газопостачання сільського населеного пункту

[![Build status][travis-image]][travis-url] [![Dependency status][dependency-image]][dependency-url]

Обчислювальні алгоритми базуються на розрахункових залежностях, які рекомендовані чинним нормативним документом

Код: [Ростислав Мінюков](https://github.com/embyth/)

Методика розрахунку: ДБН В.2.5-20 "Газопостачання"

[**Онлайн-розрахунок**](https://embyth.github.io/gas-supply-systems/)

---

## Зміст

- [:cyclone: Розрахунок системи газопостачання сільського населеного пункту](#cyclone-розрахунок-системи-газопостачання-сільського-населеного-пункту)
  - [Зміст](#зміст)
  - [Структура проекту](#структура-проекту)

---

## Структура проекту

```bash
.
├── build/            # директорія сборки проекту (генерується автоматично)
├── dist/             # директорія проекту для архівування (генерується автоматично)
├── gulp/             # директорія задач Gulp
├── source/           # директорія вихідних файлів проекту
│   ├── fonts/        # директорія шрифтів
│   ├── img/          # директорія картинок
│   ├── js/           # директорія JavaScript файлів
│   ├── sass/         # директорія стилів
│   └── index.html    # головний файл розмітки
├── .babelrc          # конфігурація Babel
├── .browserslistrc   # конфігурація browserslist
├── .editorconfig     # конфігурація Editor config
├── .eslintignore     # виключення ESlint
├── .eslintrc.yml     # конфігурація ESLint
├── .gitattributes    # файл Git attributes
├── .gitignore        # файл Git ignore
├── .npmrc            # конфігурація npm
├── .stylelintrc.json # конфігурація stylelint
├── .travis.yml       # конфігураціяTravis CI
├── gulpfile.js       # концігурація Gulp
├── webpack.config.js # конфігурація Webpack
├── package.json      # файл npm залежностей та налаштування проекту
├── package-lock.json # npm lock-file
└── README.md         # документація
```

---

[travis-image]: https://travis-ci.org/embyth/gas-supply-systems.svg?branch=master
[travis-url]: https://travis-ci.org/embyth/gas-supply-systems
[dependency-image]: https://david-dm.org/embyth/gas-supply-systems/dev-status.svg?style=flat-square
[dependency-url]: https://david-dm.org/embyth/gas-supply-systems?type=dev

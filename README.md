# Партнерский виджет "Калькулятор криптовалют"

Виджет калькулятора предоставляет калькулятор конвертации валют по курсам.

![widget picture](/img/index.png)

## Установка

Для установки виджета нужно скачать последнею версию виджета тут
[garantex-widget-calculator.js](https://github.com/garantexio/calculator-widget/releases/download/1.0.0/garantex-calculator-widget.js)

Добавить на страницу в нужное место контейнер в котором будет происходить инициализация виджета.

```html
<div id="garantex-calculator-widget"></div>
```

И в конец файла вставить, перед тегом body вставить

```html
<script type="module" src="garantex-calculator-widget.js"></script>
```

## Настройка

У виджета есть 3 цветовой вариации:

- light
- green
- dark

Тему виджета можно поменять, указав цвет темы `data-theme` контейнера:

`data-theme="light"`

`data-theme="green"`

`data-theme="dark"`

У виджета два языка: русский(ru) и английский(en). Поменять язык можно указав data-lang контейнера:

`data-lang="ru"`
`data-lang="en"`

По умолчанию кнопка “Подробнее” ведет на выбранную пользователем пару в самом калькуляторе.

Например: Выбранная пара ETH/RUB перенаправит пользователя на биржу, во вкладку торги, в пару ETH/RUB – https://garantex.io/trading/ethrub .

![widget picture](/img/index2.png)

Партнер может “вшить” в кнопку “Подробнее” свою реферальную ссылку. Для этого ему необходимо будет вставить дополнительную строчку в код.

`data-ref="https://garantex.io/invite/XxXxXx"`

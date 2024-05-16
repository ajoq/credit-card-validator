[![Build status](https://ci.appveyor.com/api/projects/status/5tpj8ydnimavv7d1?svg=true)](https://ci.appveyor.com/project/ajoq/credit-card-validator)

https://ajoq.github.io/js-credit-card-validator/

---

### Credit Card Validator

Виджет, позволяющий вводить номер карты:

![](./pic/validator.png)

Скриншот взят с сайта http://www.validcreditcardnumber.com.

#### Описание

Использовать [алгоритм Луна](https://en.wikipedia.org/wiki/Luhn_algorithm) для проверки валидности номера карты.

Источник номеров карт [FreeFormatter](https://www.freeformatter.com/credit-card-number-generator-validator.html).

---

### Puppeteer

Подключить Puppeteer и проверить взаимодействие для двух различных вариантов:
1. Ввод валидного номера карты
1. Ввод невалидного номера краты

---

### JSDOM

Подключить JSDOM и реализовать проверку с использованием `jest.each`.

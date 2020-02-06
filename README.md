[На русском](#ru)

#### *EN*

# RegExp Form
## A sample form which uses regular expressins for input validation

#### Input fields:

1. Name
   + accepts cyrillic characters *only*, 2 to 20 symbols
   + first letter of every word must be capitalized
   + double names separated by dash are allowed

2. Email
   + accepts only latin characters, underscores, digits and dash symbols
   + **@** and **.** are mandatory symbols

3. Phone number
   - acceptable formats:
     + +7 (925) 900-90-90
     + +7(925)900-90-90
     + +7(925) 900-90-90
     + +7 925-900-90-90
     + +79259009090
     + 89259009090
     * +380 (99) 335-88-88
     * +7 (77732) 333-33

4. Web site
   * must start with *http://* or *https://*
   * must contain a domain name or an IP address; *supports cyrillic domain names*
   * could contain: *www*, port (*:8080) - 2 to 5 digits after a colon,
   * could contain: path - latin characters, slashes and digits
   * could contain: one hash character (*#*) at the end

#### Tech used in this project: 
+ native JavaScript
+ CSS
+ HTML
+ regular expressions; [here's a useful tool for online testing](https://regex101.com/)
+ [GitHub Pages](https://pages.github.com/)

#### *RU*

# Форма с регэкспами
## Форма, использующая регулярные выражения для валидации полей

#### Поля:

1. Name
   + имя или имя + фамилия
   + подходят *только* кириллические символы, от 2 до 20
   + первая буква каждого из слов должна быть прописной
   + допустимы двойные имена, разделенные дефисом или тире

2. Email
   + только латиница, нижние подчеркивания, дефисы (минусы) или цифры
   + символы **@** и **.** обязательны

3. Телефон
   - допустимые форматы:
     + +7 (925) 900-90-90
     + +7(925)900-90-90
     + +7(925) 900-90-90
     + +7 925-900-90-90
     + +79259009090
     + 89259009090
     * +380 (99) 335-88-88
     * +7 (77732) 333-33

4. Сайт
   * адрес должен начинаться с протокола: *http://* или *https://*
   * должен содержать доменное имя или IP-адрес; *поддерживаются кириллические доменные имена*
   * также может содержать: *www*, порт (*:8080) - от 2 до 5 символов после двоеточия
   * также может содержать: путь - последовательность, состоящая из латиницы, слэшей и цифр
   * также может содержать: один символ *#* в конце

#### Использованы технологии 
+ нативный JavaScript
+ CSS
+ HTML
+ регулярные выражения; [вот полезный инструмент для онлайн-тестирования](https://regex101.com/)
+ [GitHub Pages](https://pages.github.com/)

[Back to top](#en)

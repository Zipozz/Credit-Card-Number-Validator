**Отчёт о тестировании Credit Card Number Validator**

**Краткое описание**

Дата начала 19.12.20> Дата окончания <19.12.20> было проведено Функциональное тестирование, тестирование документации. приложения **Credit Card Number Validator.**

**На тестирование затрачено:** 1 час

**В результате тестирования выявлены следующие дефекты:**

- https://github.com/Zipozz/Credit-Card-Number-Validator/issues/1
- https://github.com/Zipozz/Credit-Card-Number-Validator/issues/2

**Описание процесса тестирования**
В процессе тестирования использовались следующие артефакты*:

[Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

В качестве тестовых данных использовались данные [источник](https://www.getcreditcardnumbers.com/generated-credit-card-numbers),
 
**Валидные номера карт.**

 **Visa**
- 4532004913298197
- 4916403268827384
- 4532897586019984
- 4916391310286131
- 4485367312609497
 
 **Mastercard**
- 5424582890453222
- 5443905241660913
- 5504226480752212
- 5274971234168151
- 5565463312937473

 **Discover**
- 6011457726119114
- 6011387506321897
- 6011642434259951
- 6011037799888371
- 6011260196777845

**Невалидные номера карт.**

**American Express**
- 376178651062267
- 372772433954173
- 349799509016363
- 348738579023082
- 372494534641431

Тестирование производилось в следующем окружении:

- ОС Windows 10 X64
- openjdk version "11.0.9.1" 2020-11-04
- OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
- OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)
- IntelliJ IDEA 2020.3 (Community Edition)
- Bild #|C-203.5981.155,built on December 1, 2020

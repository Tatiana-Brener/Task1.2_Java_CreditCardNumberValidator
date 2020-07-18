## Краткое описание

17.07.2020  было проведено функциональное тестирование и тестирование по эквивалентным значениям с позитивными и негативными значениями приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

## В результате тестирования выявлены следующие дефекты:

1. [В IDEA при вводе валидного номера кредитной карты больше 16 цифр получаем результат FAIL вместо OK](https://github.com/Tatiana-Brener/Task1.2_Java_CreditCardNumberValidator/issues/2)
1. [В IDEA при вводе валидного номера кредитной карты меньше 16 цифр получаем результат FAIL вместо OK](https://github.com/Tatiana-Brener/Task1.2_Java_CreditCardNumberValidator/issues/3)

## Описание процесса тестирования

### В процессе тестирования использовались следующие артефакты:

- [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
- [Программный код, который реализует функциональность валидации номера банковской карты](https://github.com/Tatiana-Brener/Task1.2_Java_CreditCardNumberValidator/blob/master/src/Main.java)
- [Файл с готовыми данными .gitignore](https://github.com/netology-code/javaqa-homeworks/blob/master/.gitignore)

### В качестве тестовых данных использовались данные <указать источник, откуда брались тестовые данные>:

- [Генератор кредитных карт](https://names.igopaygo.com/ru/Кредитные-карты)
- [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html)

## Тестирование производилось в следующем окружении:

- MacBook Air (13-inch, Early 2015), версия 10.12.6
- Open JDK version "11.0.7" 2020-04-14
- IntelliJ IDEA
# Отчёт о тестировании  ValidCardNumber

## Краткое описание

04.03.2021 было проведено функциональное тестирование приложения ValidCardNumber .

На тестирование затрачено: 4 часа

В результате тестирования выявлены следующие дефекты:
* [Валидатор определяет карты "American Express" как не валидные](https://github.com/skirios/homework_java1.2/issues/2)
* [Валидатор определяет карты "Мир" как не валидные](https://github.com/skirios/homework_java1.2/issues/1)


## Описание процесса тестирования

В качестве тестовых данных использовались данные:
* [Генератор случайных номеров карт "Мир"](https://creditcardgenerator.in/card-generator/mir)
* [Генератор случайных номеров карт](https://www.prepostseo.com/tool/ru/credit-card-generator)

Тестирование производилось в следующем окружении:
* ubuntu 20.04.2
* openjdk 11.0.10
* IntelliJ IDEA 


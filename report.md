# Отчёт о тестировании кода программы, определяющего валидность номера номера банковской карты.

## Краткое описание

<01.05.2020> - <01.05.2020> было проведено функциональное тестирование (методом чёрного ящика с использованием эквивалентного разбиения) кода программы, определяющего валидность номера банковской карты.

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
*  https://github.com/NekrasovaMarina/dz1_java_task2new2/issues/1
*  https://github.com/NekrasovaMarina/dz1_java_task2new2/issues/2
*  https://github.com/NekrasovaMarina/dz1_java_task2new2/issues/3

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* баг-репорт 1
* баг-репорт 2
* баг-репорт 3
* отчёт о тестировании

В качестве тестовых данных использовались данные:
* данные: https://www.freeformatter.com/credit-card-number-generator-validator.html
*  класс эквивалентности 1: карты VIZA, Discover и JCB с валидным номером из 19 знаков
*  класс эквивалентности 2: карты Diners Club - Carte Blanche и Diners Club - International с валидным номером из 14 знаков
*  класс эквивалентности 3: карты American Express (AMEX) с валидным номером из 15 знаков
*  класс эквивалентности 4: карты VIZA, Discover, Visa Electron, MasterCard, JCB, InstaPayment, Diners Club - North America, Maestro с валидным номером из 16 знаков
* ожидаемый результат: 
 ОК

Тестирование производилось в следующем окружении:
* Windows 10 Pro 64-разрядная
* java version "11.0.7" 2020-04-14
* IntelliJ IDEA Community
* терминал Git
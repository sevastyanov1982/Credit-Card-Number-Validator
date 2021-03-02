# Отчёт о тестировании Credit Card Number Validator

### Краткое описание

02.03.2021 было проведено функциональное тестирование и тестирование форм ввода с использованием позитивного и негативного тестирования приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

 - [Не принимает валидный номер карты Visa при вводе в приложении Credit Card Number Validator](https://github.com/sevastyanov1982/Credit-Card-Number-Validator/issues/1#issue-820247415)
 - [Не принимает валидный номер карты Discover при вводе в приложении Credit Card Number Validator](https://github.com/sevastyanov1982/Credit-Card-Number-Validator/issues/2#issue-820262077)
 - [Не принимает валидный номер карты JCB при вводе в приложении Credit Card Number Validator](https://github.com/sevastyanov1982/Credit-Card-Number-Validator/issues/3#issue-820278225)
 - [Не принимает валидный номер карты Diners Club - International при вводе в приложении Credit Card Number Validator](https://github.com/sevastyanov1982/Credit-Card-Number-Validator/issues/4#issue-820282551)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

- [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)


В качестве тестовых данных использовались данные сгенерированные номера валидных карт [freeformatter.com](https://freeformatter.com/credit-card-number-generator-validator.html):

- Result for MasterCard 2221002006524123 - OK
- Result for Maestro 6763651577815495 - OK
- Result for Visa 4929123735348526 - OK
- Result for Visa Electron 4508497210529944 - OK
- Result for JCB 3537015314851951 - OK
- Result for Diners Club - International 36851953915620 - FAIL
- Result for JCB 3528633662966518531 - FAIL
- Result for Discover 6011973862476228116 - FAIL
- Result for Visa 4024007162092351276 - FAIL


Тестирование производилось в следующем окружении:

- MacOS Big Sur Версия 11.2.2
- JDK build 11.0.10+9
- IntelliJ IDEA
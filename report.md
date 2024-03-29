# Отчёт о тестировании <Payment Assistance>

## Краткое описание

16.07.2021 - 18.07.2021 было проведено тестирование методом эквивалентных значений приложения Payment Assistance.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты: [Описание дефекта](https://github.com/EvgeniyaZavyalova/JavaHW1/issues/1#issue-947799482https://github.com/EvgeniyaZavyalova/JavaHW1/issues/1#issue-947799482)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
 Инструкция по установке [IntelliJ IDEA]( https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md).

В качестве тестовых данных использовались данные с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* VISA 4556511050273248 Result is OK
* VISA 4916552828377399273 Result is OK
* Discover 6011367970827645 Result is OK
* Discover 6011605926442612590 Result is OK
* Diners Club - Carte Blanche 30590666619113 Result is OK
* Visa Electron 4508385533881961 Result is OK 
* MasterCard 5568331821434430 Result is OK
* JCB 3589090181015334 Result is OK
* JCB 3534916356718295177 Result is OK
* Diners Club - International 36469553462388 Result is OK
* InstaPayment 6377622823529238 Result is OK>
* American Express (AMEX) 375188352346472 Result is OK
* Diners Club - North America 5475803543308482 Result is OK
* Maestro 6761638083672348 Result is OK

## Тестирование производилось в следующем окружении:
* Windows 10 Pro 1903 12.02.2021 18362.295 64-разрядная ОС
* версия Java 11.0.11

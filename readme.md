# Отчёт о тестировании Precision

## Краткое описание

21.07.21 - 21.07.21 было проведено санитарное тестирование приложения Precision.

На тестирование затрачено: 1 ч

В результате тестирования выявлены следующие дефекты:
* [Суммарный бонус для новых клиентов не соответствует ожидаемому при добавлении дополнительного бонуса](https://github.com/SvetlanaKS/HWJ22/issues/1#issue-949495770)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Баг-репорты
* Отчет о тестировании


В качестве тестовых данных использовались входные данные задачи:
* переменная типа double значение 0.3
* переменная типа double значение 0.6
* переменная для хранения итогового значения - тип double

Тестирование производилось в следующем окружении:
* Windows 10 Pro версия 21H1 64-разрядная операционная система,процессор x64
* Java version "11.0.11" 2021-04-20
# Отчёт о тестировании Bonus Service

## Краткое описание

2 августа 2021 г. - 3 августа 2021 г. было проведено приемочное приложения Bonus Service.

На тестирование затрачено: 3 часа 

В результате тестирования выявлены следующие дефекты:
* [В строке total bonus выводится не суммарное значение regular bonus и special bonus](https://github.com/pauline-qa/Java1.2_task2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Тест-план](https://docs.google.com/spreadsheets/d/136AXPCEPA8M7TuVNPJv5XKroqRyk1IMHBIpyCaHF8Ug/edit?usp=sharing)


В качестве тестовых данных использовались данные из файла по [ссылке](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):
* Обычный бонус 0.3 и дополнительный бонус 0.6. Ожидаемый результат: 0.9.

Тестирование производилось в следующем окружении:
* macOS Big Sur Version 11.4
* openjdk version "11.0.11" 2021-04-20
* OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)
* OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)
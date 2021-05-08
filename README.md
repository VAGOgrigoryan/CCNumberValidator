# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

08.05.2021-08.05.2021 было проведено тестирование на валидацию карты приложения Credit Card Number Validator

На тестирование затрачено: 1,5 часа

В результате тестирования выявлены следующие дефекты:
* не проходят процесс валидации некоторые карт, https://github.com/VAGOgrigoryan/CCNumberValidator/issues/1#issue-881040970

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Установить IntelliJ IDEA согласно Руководство по установке IntelliJ IDEA
* Номера валидных карт, которые взяты с сайта freeformatter.com


В качестве тестовых данных использовались данные <указать источник, откуда брались тестовые данные>:
Данные валидных карт были автоматически сгенерированы на сайте freeformatter.com
* 4716826015262236
* 4716137654663720
* 4929657224852316445

Тестирование производилось в следующем окружении:
* Windows 10 Pro x64
* Java 11.0.10
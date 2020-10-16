# Домашнее задание к занятию «4.1. Репортинг»
Добавление системы отчетности Allure в [проект](https://github.com/usoltsevjr/NewDeliveryCard)

## Начало работы 
1. Скачать [проект](https://github.com/usoltsevjr/Allure) используя команду Git clone и ссылку проекта


## Prerequisites 
1. Git
1. Intellij IDEA
1. Java 11
1. Google Chrome

## Установка и запуск
1. Открыть проект в IntelliJ IDEA
1. Перейти на вкладку терминал и запустить SUT командой `java -jar artifacts/app-card-delivery.jar`
1. Перейти в scr/test/java/ru.netology.web и выбрать *CardDeliveryTest*
1. Запустить выполнение тестов 
1. Ввести в терминале команду `gradlew allureServe`
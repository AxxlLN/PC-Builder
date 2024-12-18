## Содержание
1. [Введение](#introduction)  
2. [Объект тестирования](#items)  
3. [Атрибуты качества](#quality)  
4. [Риски](#risk)  
5. [Аспекты тестирования](#features)  
6. [Подходы к тестированию](#approach)  
7. [Представление результатов](#pass)  
8. [Выводы](#conclusion)

<a name="introduction"/>

## Введение

Этот документ описывает план тестирования Android-приложения **PcBuilder**, предназначенного для составления сборок ПК, добавления комплектующих в избранное, поиска готовых сборок, настройки интерфейса и управления профилем пользователя. Цель тестирования — удостовериться, что приложение удовлетворяет всем требованиям функциональности, безопасности и производительности.

<a name="items"/>

## Объект тестирования

Объекты тестирования приложения **PcBuilder** включают следующие функциональные требования:

- Регистрация и вход в аккаунт;
- Просмотр и редактирование профиля;
- Составление сборок ПК;
- Добавление комплектующих в избранное;
- Поиск и редактирование готовых сборок;
- Настройка темы приложения.

<a name="quality"/>

## Атрибуты качества

1. **Функциональность**:
   - Все заявленные функции, такие как регистрация, создание и редактирование сборок, должны работать корректно.
   
2. **Удобство использования**:
   - Пользовательский интерфейс должен быть интуитивно понятным, навигация — простой и логичной.

3. **Производительность**:
   - Приложение должно быть быстрое, время отклика не должно превышать 2 секунд на выполнение команд.

4. **Безопасность**:
   - Все данные пользователей должны быть защищены, ошибки безопасности должны быть минимизированы.

<a name="risk"/>

## Риски

Риски для проекта могут включать:

- Потеря данных пользователя из-за сбоя в базе данных;
- Проблемы с производительностью при большой нагрузке, например, из-за использования сторонних библиотек для компиляции кода.
- Возможные ошибки при проверке совместимости комплектующих в сборках.

<a name="features"/>

## Аспекты тестирования

При тестировании приложения **PcBuilder** будут проверяться следующие функциональные области:

- Запуск приложения и регистрация пользователя;
- Отображение данных профиля и возможность обновления пароля;
- Добавление комплектующих из каталога в сборку;
- Проверку совместимости выбранных комплектующих;
- Сохранение и редактирование сборки.
- Добавление и удаление товаров из избранного.
- Поиск готовых сборок по фильтрам (цена, назначение).
- Редактирование и сохранение готовых сборок.
- Переключение между светлой и тёмной темами.
- Сохранение выбранной темы при перезапуске приложения.

<a name="approach"/>

## Подходы к тестированию

При тестировании будет использоваться **ручной подход** с фокусом на функциональное тестирование каждого из заявленных процессов.

<a name="pass"/>

## Представление результатов

Результаты будут представлены в документе **“[Результаты тестирования](https://github.com/AxxlLN/PC-Builder/blob/main/docs/tests/TestResult.md)”**, доступном в репозитории проекта.

<a name="conclusion"/>

## Выводы

Данный план тестирования охватывает все ключевые функции приложения **PcBuilder**. Успешное прохождение тестов позволит удостовериться в том, что приложение работает корректно и соответствует ожидаемым требованиям, но не гарантирует его идеальную работу на всех устройствах и версиях ОС.

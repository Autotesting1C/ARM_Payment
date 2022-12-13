# Паспорт автоматизации проекта АРМ Выплат


|                                       |                                                                                                                                                               |
| :------------------------------------ |:--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Заказчик:**                             | Корольков Василий Юрьевич                                                                                                                                     |
| **Разработчик:**                      | Захаров Евгений Валерьевич                                                                                                                                    |
| **Автоматизатор:**                    | Сузько Александр Анатольевич                                                                                                                                  |
| **Цель:**                                 | Автоматизация проверки полного цикла выплаты выигрышей в АРМ выплат для баз ТКЦ, ГСЛ и Спортлото. Обеспечить покрытие конфигурации дымовыми тестами.          |
| **Инструменты:**                          | Vanessa Automation, Gitlab, Jenkins                                                                                                                           |
| **Среда разработки/запуска автотестов:**  | TIFA (GA)                                                                                                                                                     |
| **Дата начала автоматизации:**            | 30.03.2022г.                                                                                                                                                  |
| **Дата завершения автоматизации:**        | -                                                                                                                                                             |
| **Количество запланированных часов:**     | 480 часов                                                                                                                                                     |
| **Количество затраченных часов:**         | 341 часов на 06.12.2022г.                                                                                                                                     |
| **Инструкция по запуску автотестов:**     | [*Инструкция*](https://confluence.tccenter.ru/pages/viewpage.action?pageId=252254051)                                                                           |
| **Документация:**                         | [*Задача на автоматизацию выплат*](https://jira.tccenter.ru/browse/IASPAY-280) <br/> [*Тест кейсы*](https://testit.tccenter.ru/projects/33976/tests?isolatedSection=2186214e-b4cc-44c8-8bc8-d2733353f718) <br/> [*Инструкция*](https://confluence.tccenter.ru/pages/viewpage.action?pageId=101390728 ) |

## Перечень тестов АРМ выплат

|   |                                                                                           |            |            |                                     |
| № | Наименование тестов                                                                       | ТКЦ        | ГСЛ        | Спортлото <br/> (пока не автоматизируем)   |
|:-:| :----------------------------------------------------------------------------------------:|:----------:|:----------:|:-----------------------------------:|
| 1 | Дымовые тесты (Справочники, Документы, Отчеты, РС, РН) (полный цикл)                      | Да         | Да         | Нет                                 |
| 2 | Безналичная выплата выигрышей (ГЕЙТ, МЛБ, ТЛБ, ВПС) (полный цикл)                         | Да         | Да         | Нет                                 |
| 3 | Наличная выплата выигрышей (ГЕЙТ, МЛБ, ТЛБ, ВПС) (полный цикл)                            | Да         | Да         | Нет                                 |
| 4 | Наличная и безналичная выплата выигрыша Нерезиденту (ГЕЙТ, МЛБ, ТЛБ, ВПС) (полный цикл)   | Да         | Да         | Нет                                 |  
| 5 | Частичные выплаты (полный цикл)                                                           | Да         | Да         | Нет                                 |
| 6 | Регистрация выплат в ручную (полный цикл)                                                 | Да         | Да         | Нет                                 |
| 7 | Проверка печати чека ККМ                                                                  | Нет        | Нет        | Нет                                 |
| 8 | Проставление фискализации выигрыша без печати чека ККМ                                    | Да         | Да         | Нет                                 |
| 9 | Идентификация участников (ГСЛ)                                                            | -          | Да         | Нет                                 |
| 10| Проставление признака ПДЛ участникам (ГСЛ)                                                | -          | Нет        | Нет                                 |
| 11| Формирование отчетов                                                                      | Нет        | Нет        | Нет                                 |
| 12| Изменение/Создание банковского счета                                                      | Да/Да      | Да/Да      | Нет/Нет                             |
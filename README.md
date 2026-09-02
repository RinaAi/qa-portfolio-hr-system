# QA Portfolio: Модуль «Моя информация» | QA Compass

![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![SRS](https://img.shields.io/badge/SRS-v2.1-blue?style=flat-square)
![Role](https://img.shields.io/badge/Role-ESS-orange?style=flat-square)

Ручное тестирование модуля **«Моя информация»** HR-системы [QA Compass](https://hr.qacompass.ru) по SRS v2.1 для роли ESS.

**Фокус:** права доступа, вложения (1 MB), валидация, динамические поля.

## Документация

| Документ | Ссылка |
|----------|--------|
| Test Plan | [test-plan.md](./docs/test-plan.md) |
| Test Summary | [test-summary.md](./docs/test-summary.md) |
| SRS v2.1 | [SRS-HR-System-v2.1.pdf](./docs/SRS-HR-System-v2.1.pdf) |
| Тест-кейсы и баг репорты | [Открыть базу](https://app.notion.com/p/QA-Portfolio-HR-System-QA-Compass-2c99eb2cc2e983fca70b01f227971ba7) |

## Результаты

- Тест-кейсов: **13** (выполнено 12)
- Passed: **11** | Failed: **1** | Blocked: **1**
- Найдено дефектов: **2** (оба High)
- Покрытие в выбранном объёме: **18/18** функциональных требований

**Дефекты:**

- BUG-PD-01 - нарушение ограничений редактирования для ESS
- BUG-PD-02 - некорректное отображение полей при уменьшении ширины окна

## Что сделано

- Анализ требований SRS v2.1
- Тест-дизайн (EP, BVA, State Transition)
- Написание и выполнение тест-кейсов
- Поиск и оформление дефектов
- Проверка NFR-01 и NFR-02

## Структура

```text
qa-portfolio-hr-system/
├── README.md
└── docs/
    ├── test-plan.md
    ├── test-summary.md
    └── SRS-HR-System-v2.1.pdf
```

# QA Portfolio: Модуль «Моя информация» | QA Compass

![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![SRS](https://img.shields.io/badge/SRS-v2.1-blue?style=flat-square)
![Role](https://img.shields.io/badge/Role-ESS-orange?style=flat-square)

Ручное тестирование модуля **«Моя информация»** HR-системы [QA Compass](https://hr.qacompass.ru) по SRS v2.1 для роли ESS.

**Фокус:** права доступа, вложения (1 MB), валидация, личные и контактные данные.

## Документация

| Документ | Ссылка |
|----------|--------|
| Test Plan | [test-plan.md](./docs/test-plan.md) |
| Test Summary | [test-summary.md](./docs/test-summary.md) |
| SRS v2.1 | [SRS-HR-System-v2.1.pdf](./docs/SRS-HR-System-v2.1.pdf) |
| Тест-кейсы и баг-репорты (Notion) | [Открыть базу](https://app.notion.com/p/QA-Portfolio-HR-System-QA-Compass-2c99eb2cc2e983fca70b01f227971ba7) |
| Полный отчёт (PDF) | [Открыть отчёт о тестировании](./QA-Portfolio-HR-System-Full.pdf) |

> **Основная база** тест-кейсов и баг-репортов ведётся в **Notion**. Если Notion недоступен — все кейсы и дефекты есть в [PDF-отчёте](./QA-Portfolio-HR-System-Full.pdf).

## Результаты

- Тест-кейсов: **14** (выполнено 14)
- Passed: **13** | Failed: **1**
- Найдено дефектов: **2** (оба High)
- Покрытие в выбранном объёме: **18/18** функциональных требований

**Дефекты:**

- BUG-PD-01 - нарушение ограничений редактирования полей для роли ESS
- BUG-PD-02 - некорректное отображение полей при уменьшении ширины окна

## Что сделано

- Анализ требований SRS v2.1
- Тест-дизайн: разбиение по классам эквивалентности, граничные значения, негативные сценарии, переходы между состояниями
- Написание и выполнение тест-кейсов
- Поиск и оформление дефектов
- Проверка нефункциональных требований: доступ по роли (NFR-01), целостность данных (NFR-02), производительность (NFR-04)

## Структура

```text
qa-portfolio-hr-system/
├── README.md
├── QA-Portfolio-HR-System-Full.pdf
└── docs/
    ├── test-plan.md
    ├── test-summary.md
    └── SRS-HR-System-v2.1.pdf
```

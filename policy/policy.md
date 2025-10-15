# Политика управления KPI

## Описание

Данный репозиторий содержит каталог KPI (Key Performance Indicators) и правила их валидации для использования в системах управления эффективностью.

## Цель

Обеспечить единообразное хранение, версионирование и валидацию KPI для интеграции с различными системами, включая Amvera.

## Структура репозитория

- **catalog/** - Каталог KPI
  - `kpi_catalog.yaml` - Основной файл с описанием всех KPI
- **rules/** - Правила валидации
  - `rules.yaml` - Правила проверки корректности KPI
- **policy/** - Документация
  - `policy.md` - Этот файл с описанием политики
- `versions.yaml` - История версий каталога

## Использование

Все файлы доступны через raw URL для интеграции с внешними системами:

```
https://raw.githubusercontent.com/easy-1c/kpi-knowledge/main/catalog/kpi_catalog.yaml
https://raw.githubusercontent.com/easy-1c/kpi-knowledge/main/rules/rules.yaml
https://raw.githubusercontent.com/easy-1c/kpi-knowledge/main/policy/policy.md
https://raw.githubusercontent.com/easy-1c/kpi-knowledge/main/versions.yaml
```

## Правила обновления

1. Все изменения должны проходить через pull request
2. При добавлении нового KPI необходимо обновить версию в versions.yaml
3. Все KPI должны соответствовать правилам из rules.yaml
4. Изменения в структуре требуют обновления данной документации

## Контакты

По вопросам обращайтесь к администратору репозитория.

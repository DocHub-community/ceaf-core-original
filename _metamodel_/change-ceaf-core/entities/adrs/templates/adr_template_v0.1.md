
Architecture Decision Record (ADR)

# {{title}}

## Общая информация


* **Статус:** {{status}}
* **Дата:** {{date}}
* **Уровень принятия решения:** {{decision_level}}
* **Автор документа:** {{doc_autor}}
* **Связь с другими решениями:** {{other_adr_links}}
    {{#other_adr_links}}
    * {{adr_link}}
    {{/other_adr_links}}

## Согласующие

| ФИО               | Должность/роль |
|:------------------|:---------------|
{{#desision_makers}}
| {{name}}          | {{role}}       |
{{/desision_makers}}

## Описание проблемы и движущих факторов изменений

### Предпосылки

{{context}}

### Цели

{{#goals}}
1. {{.}}
{{/goals}}

### Границы изменений

{{#boarders}}
1. {{.}}
{{/boarders}}

## Принятое решение

{{decision_taken}}

## Последствия
{{consequences}}

## Рассмотренные варианты

{{#considered_options}}
{{option_number}}. {{option_name}} - {{option_description}}
{{/considered_options}}


<!-- Разделы выше обязательные -->

## Описание бизнес-процесса

## Архитектура решения

## Приложения


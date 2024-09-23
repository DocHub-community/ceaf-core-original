# Метамодель управления прикладной архитектурой

Данный репозиторий является эволюционным развитием [Community Enterprise Architecture Framework (CEAF)](https://github.com/rpiontik/ceaf-core-original/blob/master/README.md).

## Цели

Основная цель данного репозитория выделить из метамодели CEAF сущности управляющие прикладным слоем архитектуры и собрать их в отдельный [архитектурный пакет archpkg](https://www.npmjs.com/package/archpkg).

## Состав поставки

```
|- datasets               - Датасеты прикладного архитектурного пакета
|- entities               - Сущности метамодели входящие в прикладной архитектурный пакет
|  |- aspects             - [Аспекты](https://dochub.info/entities/docs/blank?dh-doc-id=dochub.aspects)
|  |  |- [файлы сущности] - Файлы сущности Аспекты описывающих её поведение
|  |  |- templates        - Шаблоны для презентаций
|  |- components          - [Компоненты](https://dochub.info/entities/docs/blank?dh-doc-id=dochub.components)
|  |  |- [файлы сущности] - Файлы сущности Компоненты описывающих ей поведение
|  |  |- templates        - Шаблоны для презентаций
|  |- contexts            - [Контексты](https://dochub.info/entities/docs/blank?dh-doc-id=dochub.contexts)
|  |  |- [файлы сущности] - Файлы сущности Контексты описывающих ей поведение
|  |  |- templates        - Шаблоны для презентаций
|  |- documents           - [Документы](https://dochub.info/entities/docs/blank?dh-doc-id=dochub.docs)
|  |  |- [файлы сущности] - Файлы сущности Документы описывающих ей поведение
|  |  |- templates        - Шаблоны для презентаций
|  |- interactions        - [Взаимодействия](https://dochub.info/entities/docs/blank?dh-doc-id=dochub.flex_metamodel.entities)
|  |  |- [файлы сущности] - Файлы сущности Взаимодействия описывающих ей поведение
|  |  |- templates        - Шаблоны для презентаций
|  |- libraries           - Библиотеки
|  |  |- [файлы сущности] - Файлы сущности библиотеки описывающих ей поведение
|  |  |- templates        - Шаблоны для презентаций
|- functions              - Функции прикладного архитектурного пакета
|- rules                  - Правила валидации прикладного архитектурного пакета
|- dochub.yaml            - Корневой манифест прикладного архитектурного пакета
|- LICENSE                - Лицензия использования прикладного архитектурного пакета
|- README.md              - Ключевая информация по прикладному архитектурному пакету
```


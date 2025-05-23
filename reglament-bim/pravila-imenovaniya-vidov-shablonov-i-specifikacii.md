---
icon: file-signature
---

# Правила именования видов, шаблонов и спецификаций

### Правила именования видов

**Схема именования вида:**

<div align="left"><figure><img src="../.gitbook/assets/image (3) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure></div>

<table><thead><tr><th width="49.85711669921875">№</th><th width="183.99993896484375">Поле</th><th width="221.5716552734375">Обязательность</th><th>Описание</th></tr></thead><tbody><tr><td>(1)</td><td>Индекс вида</td><td>Обязательно</td><td>Определяет назначение вида (см. таблицу 1)</td></tr><tr><td>(2)</td><td>Раздел</td><td>Обязательно</td><td>Раздел (или подраздел) проекта</td></tr><tr><td>(3)</td><td>Стадия</td><td>Обязательно для индекса <code>О</code></td><td>Стадия проекта</td></tr><tr><td>(4)</td><td>Зона/Сегмент</td><td>Опционально</td><td>Используется при делении вида на зоны</td></tr><tr><td>(5)</td><td>Уровень с отметкой</td><td>Обязательно для планов этажей и потолков</td><td>Обозначение уровня в формате <code>[Номер уровня]_[Отметка уровня]</code></td></tr><tr><td>(6)</td><td>Код семейства вида</td><td>Обязательно</td><td>Код типа вида (см. таблицу 2)</td></tr><tr><td>(7)</td><td>Описание</td><td>Опционально</td><td>Название вида в штампе</td></tr></tbody></table>

#### Таблица 1: Назначение видов

<table><thead><tr><th width="232.4285888671875">Назначение</th><th width="113.5714111328125">Индекс</th><th>Примечание</th></tr></thead><tbody><tr><td>01-КООРДИНАЦИЯ</td><td>ЗВ</td><td>Задание входящее</td></tr><tr><td></td><td>ЗИ</td><td>Задание исходящее</td></tr><tr><td></td><td>К</td><td>Координация</td></tr><tr><td>02-ВСПОМОГАТЕЛЬНЫЕ</td><td>В</td><td>Вспомогательный вид (не размещается на листах)</td></tr><tr><td>03-ОФОРМЛЕНИЕ</td><td>О</td><td>Основной вид (идет на лист)</td></tr><tr><td></td><td>И</td><td>Изображение (визуализация)</td></tr><tr><td></td><td>Э</td><td>Вид для экспорта в другое ПО</td></tr></tbody></table>

#### Таблица 2: Коды семейств видов

<table><thead><tr><th width="132.28570556640625">Код</th><th>Описание</th></tr></thead><tbody><tr><td>ПЭ</td><td>Планы этажей</td></tr><tr><td>ПП</td><td>Планы потолков</td></tr><tr><td>ПЗ</td><td>Планы зонирования</td></tr><tr><td>Р</td><td>Разрезы</td></tr><tr><td>У</td><td>Фрагменты плана, узлы</td></tr><tr><td>Ф</td><td>Фасады</td></tr><tr><td>ГП</td><td>Генеральный план, ПЗУ</td></tr><tr><td>Ч</td><td>Чертежный вид</td></tr><tr><td>Л</td><td>Легенды</td></tr><tr><td>3D</td><td>3D Виды</td></tr></tbody></table>

### Правила именования шаблона вида

Шаблон вида именуется аналогично видам. **Схема именования:**

<div align="left"><figure><img src="../.gitbook/assets/image (4) (1).png" alt="" width="530"><figcaption></figcaption></figure></div>

Описание полей см. в разделе [Правила именования видов](pravila-imenovaniya-vidov-shablonov-i-specifikacii.md#pravila-imenovaniya-vidov)

### Правила именования спецификаций

**Схема именования спецификации:**

<div align="left"><figure><img src="../.gitbook/assets/image (5) (1).png" alt="" width="563"><figcaption></figcaption></figure></div>

<table><thead><tr><th width="56.1429443359375">№</th><th width="156.85723876953125">Поле</th><th width="175">Обязательность</th><th>Описание</th></tr></thead><tbody><tr><td>(1)</td><td>Индекс вида</td><td>Обязательно</td><td>Определяет назначение вида (см. таблицу 1)</td></tr><tr><td>(2)</td><td>Раздел</td><td>Обязательно</td><td>Раздел проекта</td></tr><tr><td>(3)</td><td>Стадия</td><td>Опционально</td><td>Указывается для сортировки</td></tr><tr><td>(4)</td><td>Зона/Сегмент</td><td>Опционально</td><td>Указывается для разделения спецификаций</td></tr><tr><td>(5)</td><td>Индекс уровня</td><td>Опционально</td><td>Используется в случае необходимости</td></tr><tr><td>(7)</td><td>Описание</td><td>Опционально</td><td>Название спецификации в штампе</td></tr></tbody></table>

### Правила именования типа вида

Для дополнительной сортировки допускается создание собственных типов видов.

**Схема именования типа вида:**

<div align="left"><figure><img src="../.gitbook/assets/image (6) (1).png" alt="" width="430"><figcaption></figcaption></figure></div>

<table><thead><tr><th width="61.85711669921875">№</th><th width="150.857177734375">Поле</th><th width="159.5711669921875">Обязательность</th><th>Описание</th></tr></thead><tbody><tr><td>(1)</td><td>Индекс вида</td><td>Обязательно</td><td>Определяет назначение вида (см. таблицу 1)</td></tr><tr><td>(2)</td><td>Стадия</td><td>Опционально</td><td>Используется для детальной сортировки</td></tr><tr><td>(3)</td><td>Описание</td><td>Обязательно</td><td>Краткое описание типа вида или применяемого шаблона</td></tr></tbody></table>

#### Примеры:

```
О_ПЭ_Маркировочный
ЗИ_ПЭ
В_Р_Канализация
```

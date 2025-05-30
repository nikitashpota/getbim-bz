# Правило именования категории "Воздуховоды"

### Схема именования

<div align="left"><figure><img src="../../.gitbook/assets/image (14) (1).png" alt="" width="375"><figcaption></figcaption></figure></div>

#### Описание полей

| № | Поле                | Обязательность | Описание                                                                                                                                                                                                 |
| - | ------------------- | -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1 | Код источника       | Опционально    | Код организации или код проекта                                                                                                                                                                          |
| 2 | Тип воздуховода     | Обязательно    | <p>Определяет конструктивные особенности:<br><strong>ПРЯМ</strong> – Прямошовный<br><strong>СВАР</strong> – Сварной<br><strong>СПИР</strong> – Спирально-навивной<br><strong>СБОР</strong> – Сборный</p> |
| 3 | Материал            | Опционально    | Указывается в соответствии с таблицей 1.5                                                                                                                                                                |
| 4 | ГОСТ, Производитель | Обязательно    | Указывается ГОСТ или производитель воздуховода                                                                                                                                                           |
| 5 | Тип соединения      | Опционально    | <p>Определяет способ соединения:<br><strong>Врезка</strong><br><strong>Тройник</strong></p>                                                                                                              |

#### Примеры именования

* **MD\_СВАР\_ЧМТ\_ГОСТ 16523\_Врезка**
* **MD\_ПРЯМ\_ОЦН\_ГОСТ 14918-80\_Тройник**

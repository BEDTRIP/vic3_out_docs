---
type: concept
description: "Метод производства «Air Mail» — LLWA 1.13, `LLWA_pm_air_mail`"
project: vic3
source: llwa
aliases: ["Air Mail", "LLWA_pm_air_mail"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_air_mail
paths: [llwa/common/production_methods/LLWA_air.txt]
---
# Air Mail

Метод производства · `LLWA_pm_air_mail` · `common/production_methods/LLWA_air.txt:72`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_air_mail.dds`
- **unlocking_production_methods**: [[llwa/Методы производства/Дирижабли|Дирижабли]], [[llwa/Методы производства/Аэропланы|Аэропланы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `10` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `30` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Airline Focus|Airline Focus]]

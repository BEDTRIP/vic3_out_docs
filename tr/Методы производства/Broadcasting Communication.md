---
type: concept
description: "Метод производства «Broadcasting Communication» — T&R 1.13, `manzoni_pm_radio`"
project: vic3
source: tr
aliases: ["Broadcasting Communication", "manzoni_pm_radio"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: manzoni_pm_radio
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Broadcasting Communication

Метод производства · `manzoni_pm_radio` · `common/production_methods/ztr_modified_mr_production_methods.txt:868`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/manzoni_transmission_radio.dds`
- **unlocking_technologies**: [[tr/Технологии/Массовая агитация|Массовая агитация]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-radios-add|goods_input_radios_add]] = `10` → [[vanilla/Товары/Радио|Радио]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `5` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_telecommunications_add` = `10` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_output_organized_data_add` = `6` → [[tr/Товары/Organized Data|Organized Data]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `1000` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Type of Communication|Type of Communication]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Color Broadcasting|Color Broadcasting]], [[tr/Методы производства/Early Broadcasting|Early Broadcasting]], [[tr/Методы производства/Electronic News Gathering|Electronic News Gathering]], [[tr/Методы производства/No Digital Media Industry|No Digital Media Industry]], [[tr/Методы производства/No Publishing Industry|No Publishing Industry]]

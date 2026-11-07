---
type: concept
description: "Метод производства «Lead-Acid Battery» — T&R 1.13, `pm_lead_acid_battery`"
project: vic3
audience: agent
source: tr
aliases: ["Lead-Acid Battery", "pm_lead_acid_battery"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_lead_acid_battery
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Lead-Acid Battery

Метод производства · `pm_lead_acid_battery` · `common/production_methods/ztr_new_production_methods.txt:4365`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/lead_acid_battery.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Электрифицированная железная дорога|Электрифицированная железная дорога]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-lead-add|goods_input_lead_add]] = `25` → [[vanilla/Товары/Свинец|Свинец]]
    - `goods_input_commonores_add` = `10` → [[tr/Товары/Common Ores|Common Ores]]
    - `goods_input_alloys_add` = `5` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-sulfur-add|goods_input_sulfur_add]] = `15` → [[vanilla/Товары/Сера|Сера]]
    - `goods_output_batteries_add` = `75` → [[tr/Товары/Batteries|Batteries]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Battery|Battery]]

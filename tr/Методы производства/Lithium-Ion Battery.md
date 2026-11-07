---
type: concept
description: "Метод производства «Lithium-Ion Battery» — T&R 1.13, `pm_lithium_battery`"
project: vic3
audience: agent
source: tr
aliases: ["Lithium-Ion Battery", "pm_lithium_battery"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_lithium_battery
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Lithium-Ion Battery

Метод производства · `pm_lithium_battery` · `common/production_methods/ztr_new_production_methods.txt:4437`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_lithium_battery.dds`
- **unlocking_technologies**: [[tr/Технологии/Lithium Ion Battery|Lithium Ion Battery]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `20`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_advancedores_add` = `5` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_rare_earths_add` = `15` → [[tr/Товары/Rare Earths|Rare Earths]]
    - `goods_input_plastics_add` = `15` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_alloys_add` = `25` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `15` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_batteries_add` = `110` → [[tr/Товары/Batteries|Batteries]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Battery|Battery]]

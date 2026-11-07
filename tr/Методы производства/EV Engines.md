---
type: concept
description: "Метод производства «EV Engines» — T&R 1.13, `pm_ev_motors`"
project: vic3
source: tr
aliases: ["EV Engines", "pm_ev_motors"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_ev_motors
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# EV Engines

Метод производства · `pm_ev_motors` · `common/production_methods/ztr_new_production_methods.txt:2174`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_ev_motors.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **unlocking_technologies**: [[tr/Технологии/Electric Vehicles|Electric Vehicles]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `40` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_batteries_add` = `25` → [[tr/Товары/Batteries|Batteries]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `20` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_processors_add` = `5` → [[tr/Товары/Processors|Processors]]
    - `goods_input_alloys_add` = `5` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-engines-add|goods_output_engines_add]] = `155` → [[vanilla/Товары/Двигатели|Двигатели]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_motor_industry)|Основа (pmg_base_building_motor_industry)]]

---
type: concept
description: "Метод производства «Prefab Concrete Buildings» — T&R 1.13, `pm_prefabricated_concrete_buildings`"
project: vic3
audience: agent
source: tr
aliases: ["Prefab Concrete Buildings", "pm_prefabricated_concrete_buildings"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_prefabricated_concrete_buildings
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_construction_production_methods.txt]
---
# Prefab Concrete Buildings

Метод производства · `pm_prefabricated_concrete_buildings` · `common/production_methods/ztr_construction_production_methods.txt:39`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/prefabricated_concrete_buildings.dds`
- **unlocking_technologies**: [[tr/Технологии/Prefabricated Concrete Buildings|Prefabricated Concrete Buildings]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-construction-add|country_construction_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `40` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_aluminium_add` = `10` → [[tr/Товары/Aluminium|Aluminium]]
    - `goods_input_alloys_add` = `10` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-glass-add|goods_input_glass_add]] = `40` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-explosives-add|goods_input_explosives_add]] = `20` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - `goods_input_robotics_add` = `15` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `30` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `100` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `50` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `200` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `300` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-construction-mult|state_construction_mult]] = `0.01`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_construction_sector)|Основа (pmg_base_building_construction_sector)]]

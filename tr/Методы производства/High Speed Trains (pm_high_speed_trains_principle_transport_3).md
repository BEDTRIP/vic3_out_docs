---
type: concept
description: "Метод производства «High Speed Trains (pm_high_speed_trains_principle_transport_3)» — T&R 1.13, `pm_high_speed_trains_principle_transport_3`"
project: vic3
source: tr
aliases: ["High Speed Trains (pm_high_speed_trains_principle_transport_3)", "High Speed Trains", "pm_high_speed_trains_principle_transport_3"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_high_speed_trains_principle_transport_3
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# High Speed Trains (pm_high_speed_trains_principle_transport_3)

Метод производства · `pm_high_speed_trains_principle_transport_3` · `common/production_methods/ztr_new_production_methods.txt:8750`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_high_speed_trains.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[tr/Технологии/Bullet Train|Bullet Train]]
- **unlocking_principles**: `principle_transport_3`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `6` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_aluminium_add` = `2` → [[tr/Товары/Aluminium|Aluminium]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `2` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_electroniccomponents_add` = `1` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `9` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `80` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `450` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `200` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `105`
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `8`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_railway)|Основа (pmg_base_building_railway)]]
- **Методы производства** (replacement_if_valid): [[tr/Методы производства/High Speed Trains (pm_high_speed_trains)|High Speed Trains (pm_high_speed_trains)]]

---
type: concept
description: "Метод производства «Autonomous Public Transport» — T&R 1.13, `pm_autonomous_city_transport`"
project: vic3
source: tr
aliases: ["Autonomous Public Transport", "pm_autonomous_city_transport"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_autonomous_city_transport
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Autonomous Public Transport

Метод производства · `pm_autonomous_city_transport` · `common/production_methods/ztr_new_production_methods.txt:6841`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_autonomous_city_transport.dds`
- **unlocking_technologies**: [[tr/Технологии/Autonomous Road Vehicles|Autonomous Road Vehicles]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `4`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-automobiles-add|goods_input_automobiles_add]] = `1` → [[tr/Товары/Автомобили|Автомобили]]
    - `goods_input_ai_systems_add` = `1` → [[tr/Товары/AI Systems|AI Systems]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `0.5` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `10` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `150` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `50` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Общественный транспорт|Общественный транспорт]]

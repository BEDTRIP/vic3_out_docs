---
type: concept
description: "Метод производства «Versatile Transportation (pm_multiway_transport_building_robotics_industry)» — T&R 1.13, `pm_multiway_transport_building_robotics_industry`"
project: vic3
audience: agent
source: tr
aliases: ["Versatile Transportation (pm_multiway_transport_building_robotics_industry)", "Versatile Transportation", "pm_multiway_transport_building_robotics_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_multiway_transport_building_robotics_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Versatile Transportation (pm_multiway_transport_building_robotics_industry)

Метод производства · `pm_multiway_transport_building_robotics_industry` · `common/production_methods/ztr_new_production_methods.txt:558`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_multiway_transport_building.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/Modern Vehicles|Modern Vehicles]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-automobiles-add|goods_input_automobiles_add]] = `2` → [[tr/Товары/Автомобили|Автомобили]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `2` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Transport (pmg_transport_automation_building_robotics_industry)|Transport (pmg_transport_automation_building_robotics_industry)]]

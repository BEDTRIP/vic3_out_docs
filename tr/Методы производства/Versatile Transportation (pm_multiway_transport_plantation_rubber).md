---
type: concept
description: "Метод производства «Versatile Transportation (pm_multiway_transport_plantation_rubber)» — T&R 1.13, `pm_multiway_transport_plantation_rubber`"
project: vic3
audience: agent
source: tr
aliases: ["Versatile Transportation (pm_multiway_transport_plantation_rubber)", "Versatile Transportation", "pm_multiway_transport_plantation_rubber"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_multiway_transport_plantation_rubber
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Versatile Transportation (pm_multiway_transport_plantation_rubber)

Метод производства · `pm_multiway_transport_plantation_rubber` · `common/production_methods/ztr_new_production_methods.txt:443`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_multiway_transport_building.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/Modern Vehicles|Modern Vehicles]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `2` → [[vanilla/Товары/Перевозка|Перевозка]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-automobiles-add|goods_input_automobiles_add]] = `2` → [[tr/Товары/Автомобили|Автомобили]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Использование поездов (pmg_train_automation_building_rubber_plantation)|Использование поездов (pmg_train_automation_building_rubber_plantation)]]

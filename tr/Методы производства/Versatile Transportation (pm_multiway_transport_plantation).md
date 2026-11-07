---
type: concept
description: "Метод производства «Versatile Transportation (pm_multiway_transport_plantation)» — T&R 1.13, `pm_multiway_transport_plantation`"
project: vic3
audience: agent
source: tr
aliases: ["Versatile Transportation (pm_multiway_transport_plantation)", "Versatile Transportation", "pm_multiway_transport_plantation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_multiway_transport_plantation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Versatile Transportation (pm_multiway_transport_plantation)

Метод производства · `pm_multiway_transport_plantation` · `common/production_methods/ztr_new_production_methods.txt:418`

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
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Transport (pmg_train_automation_building_hydroponic)|Transport (pmg_train_automation_building_hydroponic)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_banana_plantation)|Использование поездов (pmg_train_automation_building_banana_plantation)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_coffee_plantation)|Использование поездов (pmg_train_automation_building_coffee_plantation)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_cotton_plantation)|Использование поездов (pmg_train_automation_building_cotton_plantation)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_dye_plantation)|Использование поездов (pmg_train_automation_building_dye_plantation)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_opium_plantation)|Использование поездов (pmg_train_automation_building_opium_plantation)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_silk_plantation)|Использование поездов (pmg_train_automation_building_silk_plantation)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_sugar_plantation)|Использование поездов (pmg_train_automation_building_sugar_plantation)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_tea_plantation)|Использование поездов (pmg_train_automation_building_tea_plantation)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_tobacco_plantation)|Использование поездов (pmg_train_automation_building_tobacco_plantation)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_vineyard)|Использование поездов (pmg_train_automation_building_vineyard)]]

---
type: concept
description: "Метод производства «Перевозка по рельсам (pm_steam_rail_transport)» — ваниль 1.15, `pm_steam_rail_transport`"
project: vic3
audience: agent
source: vanilla
aliases: ["Перевозка по рельсам (pm_steam_rail_transport)", "Rail Transportation", "pm_steam_rail_transport"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_rail_transport
paths: [.vanillaVIC3/common/production_methods/04_plantations.txt]
---
# Перевозка по рельсам (pm_steam_rail_transport)

Метод производства · `pm_steam_rail_transport` · `common/production_methods/04_plantations.txt:137`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_transport.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `5` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_banana_plantation)|Использование поездов (pmg_train_automation_building_banana_plantation)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_coffee_plantation)|Использование поездов (pmg_train_automation_building_coffee_plantation)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_cotton_plantation)|Использование поездов (pmg_train_automation_building_cotton_plantation)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_dye_plantation)|Использование поездов (pmg_train_automation_building_dye_plantation)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_opium_plantation)|Использование поездов (pmg_train_automation_building_opium_plantation)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_rubber_plantation)|Использование поездов (pmg_train_automation_building_rubber_plantation)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_silk_plantation)|Использование поездов (pmg_train_automation_building_silk_plantation)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_sugar_plantation)|Использование поездов (pmg_train_automation_building_sugar_plantation)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_tea_plantation)|Использование поездов (pmg_train_automation_building_tea_plantation)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_tobacco_plantation)|Использование поездов (pmg_train_automation_building_tobacco_plantation)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_vineyard)|Использование поездов (pmg_train_automation_building_vineyard)]]

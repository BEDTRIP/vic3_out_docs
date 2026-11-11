---
type: concept
description: "Метод производства «Перевозка по рельсам (pm_rail_transport_mine)» — ваниль 1.15, `pm_rail_transport_mine`"
project: vic3
audience: agent
source: vanilla
aliases: ["Перевозка по рельсам (pm_rail_transport_mine)", "Перевозка по рельсам", "pm_rail_transport_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rail_transport_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Перевозка по рельсам (pm_rail_transport_mine)

Метод производства · `pm_rail_transport_mine` · `common/production_methods/03_mines.txt:420`

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

- **Группы методов** (методы группы): [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_coal_mine)|Использование поездов (pmg_train_automation_building_coal_mine)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_copper_mine)|Использование поездов (pmg_train_automation_building_copper_mine)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_gold_mine)|Использование поездов (pmg_train_automation_building_gold_mine)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_iron_mine)|Использование поездов (pmg_train_automation_building_iron_mine)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_lead_mine)|Использование поездов (pmg_train_automation_building_lead_mine)]], [[vanilla/Группы методов/Использование поездов (pmg_train_automation_building_sulfur_mine)|Использование поездов (pmg_train_automation_building_sulfur_mine)]]

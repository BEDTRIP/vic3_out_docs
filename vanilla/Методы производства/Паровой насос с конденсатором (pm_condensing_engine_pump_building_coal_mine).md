---
type: concept
description: "Метод производства «Паровой насос с конденсатором (pm_condensing_engine_pump_building_coal_mine)» — ваниль 1.15, `pm_condensing_engine_pump_building_coal_mine`"
project: vic3
audience: agent
source: vanilla
aliases: ["Паровой насос с конденсатором (pm_condensing_engine_pump_building_coal_mine)", "Condensing Engine Pump", "pm_condensing_engine_pump_building_coal_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_condensing_engine_pump_building_coal_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Паровой насос с конденсатором (pm_condensing_engine_pump_building_coal_mine)

Метод производства · `pm_condensing_engine_pump_building_coal_mine` · `common/production_methods/03_mines.txt:51`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/condensing_engine_pump.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-coal-add|goods_output_coal_add]] = `60` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Горнодобывающее оборудование (pmg_mining_equipment_building_coal_mine)|Горнодобывающее оборудование (pmg_mining_equipment_building_coal_mine)]]

---
type: concept
description: "Метод производства «Condensing Engine Pump (pm_condensing_engine_pump_building_copper_mine)» — T&R 1.13, `pm_condensing_engine_pump_building_copper_mine`"
project: vic3
source: tr
aliases: ["Condensing Engine Pump (pm_condensing_engine_pump_building_copper_mine)", "Condensing Engine Pump", "pm_condensing_engine_pump_building_copper_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_condensing_engine_pump_building_copper_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Condensing Engine Pump (pm_condensing_engine_pump_building_copper_mine)

Метод производства · `pm_condensing_engine_pump_building_copper_mine` · `common/production_methods/ztr_new_production_methods.txt:4934`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/condensing_engine_pump.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `20`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `15` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_copper_add` = `60` → [[tr/Товары/Copper|Copper]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_copper_mine)|Mining Equipment (pmg_mining_equipment_building_copper_mine)]]

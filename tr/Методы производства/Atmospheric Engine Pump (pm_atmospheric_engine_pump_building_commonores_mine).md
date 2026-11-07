---
type: concept
description: "Метод производства «Atmospheric Engine Pump (pm_atmospheric_engine_pump_building_commonores_mine)» — T&R 1.13, `pm_atmospheric_engine_pump_building_commonores_mine`"
project: vic3
audience: agent
source: tr
aliases: ["Atmospheric Engine Pump (pm_atmospheric_engine_pump_building_commonores_mine)", "Atmospheric Engine Pump", "pm_atmospheric_engine_pump_building_commonores_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_atmospheric_engine_pump_building_commonores_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Atmospheric Engine Pump (pm_atmospheric_engine_pump_building_commonores_mine)

Метод производства · `pm_atmospheric_engine_pump_building_commonores_mine` · `common/production_methods/ztr_new_production_methods.txt:5090`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pumps.dds`
- **unlocking_technologies**: [[tr/Технологии/Пароатмосферный двигатель|Пароатмосферный двигатель]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `10` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_commonores_add` = `40` → [[tr/Товары/Common Ores|Common Ores]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_commonores_mine)|Mining Equipment (pmg_mining_equipment_building_commonores_mine)]]

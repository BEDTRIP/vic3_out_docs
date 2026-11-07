---
type: concept
description: "Метод производства «Конвейерное производство (pm_assembly_lines_building_motor_industry)» — TGR 1.13, `pm_assembly_lines_building_motor_industry`"
project: vic3
source: tgr
aliases: ["Конвейерное производство (pm_assembly_lines_building_motor_industry)", "Assembly Lines", "pm_assembly_lines_building_motor_industry"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_assembly_lines_building_motor_industry
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Конвейерное производство (pm_assembly_lines_building_motor_industry)]]"
---
# Конвейерное производство (pm_assembly_lines_building_motor_industry)

Метод производства · `pm_assembly_lines_building_motor_industry` · `common/production_methods/TGR_TRADE_automation.txt:534`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/assembly_lines.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **unlocking_technologies**: [[vanilla/Технологии/Конвейеры|Конвейеры]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `3` → [[tgr/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `1` → [[tgr/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `1` → [[tgr/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-500` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-1000` → [[vanilla/Население/Типы/Механики|Механики]]
- **required_input_goods**: [[tgr/Товары/Электричество|Электричество]]

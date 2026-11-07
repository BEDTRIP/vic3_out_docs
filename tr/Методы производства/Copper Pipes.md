---
type: concept
description: "Метод производства «Copper Pipes» — T&R 1.13, `pm_copper_pipes`"
project: vic3
audience: agent
source: tr
aliases: ["Copper Pipes", "pm_copper_pipes"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_copper_pipes
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Copper Pipes

Метод производства · `pm_copper_pipes` · `common/production_methods/ztr_new_production_methods.txt:6538`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_copper_pipe.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copper_add` = `9` → [[tr/Товары/Copper|Copper]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `6` → [[vanilla/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-450` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_water_plant)|Automation (pmg_automation_building_water_plant)]]

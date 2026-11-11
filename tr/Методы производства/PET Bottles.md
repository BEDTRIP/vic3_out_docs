---
type: concept
description: "Метод производства «PET Bottles» — T&R 1.13, `pm_plastics_pipes_and_pet`"
project: vic3
audience: agent
source: tr
aliases: ["PET Bottles", "pm_plastics_pipes_and_pet"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_plastics_pipes_and_pet
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# PET Bottles

Метод производства · `pm_plastics_pipes_and_pet` · `common/production_methods/ztr_new_production_methods.txt:6575`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_bottles.dds`
- **unlocking_technologies**: [[tr/Технологии/Polyester Synthesis|Polyester Synthesis]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_copper_add` = `3` → [[tr/Товары/Медь|Медь]]
    - `goods_input_plastics_add` = `12` → [[tr/Товары/Пластмассы|Пластмассы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `6` → [[vanilla/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Automation (pmg_automation_building_water_plant)|Automation (pmg_automation_building_water_plant)]]

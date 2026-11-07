---
type: concept
description: "Метод производства «Oxygen Steelmaking Furnace» — T&R 1.13, `pm_oxygen_steel_process`"
project: vic3
source: tr
aliases: ["Oxygen Steelmaking Furnace", "pm_oxygen_steel_process"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_oxygen_steel_process
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Oxygen Steelmaking Furnace

Метод производства · `pm_oxygen_steel_process` · `common/production_methods/ztr_new_production_methods.txt:112`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_oxygen_steelmaking_process.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `20`
- **unlocking_technologies**: [[tr/Технологии/Oxygen Steelmaking Process|Oxygen Steelmaking Process]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_iron_add` = `100` → [[vanilla/Товары/Железо|Железо]]
    - `goods_input_coal_add` = `20` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_electricity_add` = `30` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_steel_add` = `170` → [[vanilla/Товары/Сталь|Сталь]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Процесс сталеварения|Процесс сталеварения]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/HYL Process|HYL Process]], [[tr/Методы производства/Midrex Process|Midrex Process]]

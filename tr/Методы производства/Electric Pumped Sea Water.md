---
type: concept
description: "Метод производства «Electric Pumped Sea Water» — T&R 1.13, `pm_electric_pumped_desalinated_water`"
project: vic3
source: tr
aliases: ["Electric Pumped Sea Water", "pm_electric_pumped_desalinated_water"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_electric_pumped_desalinated_water
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Electric Pumped Sea Water

Метод производства · `pm_electric_pumped_desalinated_water` · `common/production_methods/ztr_new_production_methods.txt:6483`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_electric_pumped_water.dds`
- **unlocking_technologies**: [[tr/Технологии/Sea Water Desalination|Sea Water Desalination]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `6` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_electricity_add` = `4` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_engines_add` = `4` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_plastics_add` = `2` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_output_water_add` = `20` → [[tr/Товары/Water|Water]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `100` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `100` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Desalination|Desalination]]

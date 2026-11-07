---
type: concept
description: "Метод производства «Advanced Sea Water Filtration» — T&R 1.13, `pm_advanced_desalinated_water_filtration`"
project: vic3
source: tr
aliases: ["Advanced Sea Water Filtration", "pm_advanced_desalinated_water_filtration"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_desalinated_water_filtration
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Sea Water Filtration

Метод производства · `pm_advanced_desalinated_water_filtration` · `common/production_methods/ztr_new_production_methods.txt:6511`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_water_filtration.dds`
- **unlocking_technologies**: [[tr/Технологии/Advanced Water Depuration|Advanced Water Depuration]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `4` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_electricity_add` = `8` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_engines_add` = `6` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_electroniccomponents_add` = `2` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_plastics_add` = `2` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_output_water_add` = `26` → [[tr/Товары/Water|Water]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `150` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `100` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Desalination|Desalination]]

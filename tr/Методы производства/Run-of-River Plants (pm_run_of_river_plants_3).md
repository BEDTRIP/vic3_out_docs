---
type: concept
description: "Метод производства «Run-of-River Plants (pm_run_of_river_plants_3)» — T&R 1.13, `pm_run_of_river_plants_3`"
project: vic3
source: tr
aliases: ["Run-of-River Plants (pm_run_of_river_plants_3)", "Run-of-River Plants", "pm_run_of_river_plants_3"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_run_of_river_plants_3
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Run-of-River Plants (pm_run_of_river_plants_3)

Метод производства · `pm_run_of_river_plants_3` · `common/production_methods/ztr_energy_production_methods.txt:182`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_run_of_river_plants.dds`
- **is_hidden_when_unavailable**: `yes`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_steel_add` = `10` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_batteries_add` = `5` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_engines_add` = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_wood_add` = `20` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_copperwires_add` = `5` → [[tr/Товары/Wires|Wires]]
    - `goods_output_electricity_add` = `15` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `155` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `2500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/Modern National Electricity System|Modern National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Hydroelectric Power Plant|Hydroelectric Power Plant]]

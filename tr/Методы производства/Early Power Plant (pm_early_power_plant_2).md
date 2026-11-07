---
type: concept
description: "Метод производства «Early Power Plant (pm_early_power_plant_2)» — T&R 1.13, `pm_early_power_plant_2`"
project: vic3
source: tr
aliases: ["Early Power Plant (pm_early_power_plant_2)", "Early Power Plant", "pm_early_power_plant_2"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_early_power_plant_2
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Early Power Plant (pm_early_power_plant_2)

Метод производства · `pm_early_power_plant_2` · `common/production_methods/ztr_energy_production_methods.txt:629`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/power_plant.dds`
- **is_hidden_when_unavailable**: `yes`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `25`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_batteries_add` = `1` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_engines_add` = `2` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_coal_add` = `4` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_input_wood_add` = `4` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_copperwires_add` = `1` → [[tr/Товары/Wires|Wires]]
    - `goods_output_electricity_add` = `15` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `15` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `325` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `100` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/National Electricity System|National Electricity System]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_power_plant)|Основа (pmg_base_building_power_plant)]]
- **Методы производства** (replacement_if_valid): [[tr/Методы производства/Ранняя электростанция|Ранняя электростанция]]

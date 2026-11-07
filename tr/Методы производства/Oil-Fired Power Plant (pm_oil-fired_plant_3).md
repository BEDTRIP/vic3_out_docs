---
type: concept
description: "Метод производства «Oil-Fired Power Plant (pm_oil-fired_plant_3)» — T&R 1.13, `pm_oil-fired_plant_3`"
project: vic3
source: tr
aliases: ["Oil-Fired Power Plant (pm_oil-fired_plant_3)", "Oil-Fired Power Plant", "pm_oil-fired_plant_3"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_oil-fired_plant_3
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Oil-Fired Power Plant (pm_oil-fired_plant_3)

Метод производства · `pm_oil-fired_plant_3` · `common/production_methods/ztr_energy_production_methods.txt:912`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/oil_fired_plant.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[vanilla/Технологии/ГСМ-турбина|ГСМ-турбина]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `50`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_batteries_add` = `2` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_engines_add` = `6` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_water_add` = `3` → [[tr/Товары/Water|Water]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
    - `goods_input_oil_add` = `25` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_electricity_add` = `9` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `90` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `200` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/Modern National Electricity System|Modern National Electricity System]]
- **disallowing_laws**: [[tr/Законы/Active Restoration|Active Restoration]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_power_plant)|Основа (pmg_base_building_power_plant)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Heavy Fuel|Heavy Fuel]], [[tr/Методы производства/Pressurized HDPE Systems (pm_pressurized_systems_power_plant)|Pressurized HDPE Systems (pm_pressurized_systems_power_plant)]], [[tr/Методы производства/Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)|Smart Grid Energy Management (pm_smart_grid_energy_management_power_plant)]]

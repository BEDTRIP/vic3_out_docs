---
type: concept
description: "Метод производства «Oil-Fired Power Plant (pm_oil-fired_plant_2)» — T&R 1.13, `pm_oil-fired_plant_2`"
project: vic3
audience: agent
source: tr
aliases: ["Oil-Fired Power Plant (pm_oil-fired_plant_2)", "Oil-Fired Power Plant", "pm_oil-fired_plant_2"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_oil-fired_plant_2
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Oil-Fired Power Plant (pm_oil-fired_plant_2)

Метод производства · `pm_oil-fired_plant_2` · `common/production_methods/ztr_energy_production_methods.txt:706`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/oil_fired_plant.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[vanilla/Технологии/ГСМ-турбина|ГСМ-турбина]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `50`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_batteries_add` = `2` → [[tr/Товары/Batteries|Batteries]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `6` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_water_add` = `3` → [[tr/Товары/Water|Water]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `25` → [[vanilla/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `50` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `55` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `525` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `200` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/National Electricity System|National Electricity System]]
- **disallowing_laws**: [[tr/Законы/Active Restoration|Active Restoration]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_power_plant)|Основа (pmg_base_building_power_plant)]]
- **Методы производства** (replacement_if_valid): [[tr/Методы производства/Мазутная электростанция|Мазутная электростанция]]

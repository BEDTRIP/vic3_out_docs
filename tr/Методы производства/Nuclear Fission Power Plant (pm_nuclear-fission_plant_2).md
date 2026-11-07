---
type: concept
description: "Метод производства «Nuclear Fission Power Plant (pm_nuclear-fission_plant_2)» — T&R 1.13, `pm_nuclear-fission_plant_2`"
project: vic3
source: tr
aliases: ["Nuclear Fission Power Plant (pm_nuclear-fission_plant_2)", "Nuclear Fission Power Plant", "pm_nuclear-fission_plant_2"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_nuclear-fission_plant_2
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Nuclear Fission Power Plant (pm_nuclear-fission_plant_2)

Метод производства · `pm_nuclear-fission_plant_2` · `common/production_methods/ztr_energy_production_methods.txt:789`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_nuclear_reactor.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[tr/Технологии/Nuclear Reactor|Nuclear Reactor]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_batteries_add` = `2` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_engines_add` = `6` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_water_add` = `10` → [[tr/Товары/Water|Water]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
    - `goods_input_electroniccomponents_add` = `3` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_good_uranium_add` = `20` → [[tr/Товары/Uranium|Uranium]]
    - `goods_output_electricity_add` = `65` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `70` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `325` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `300` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/National Electricity System|National Electricity System]]
- **disallowing_laws**: [[tr/Законы/Uranium Ban|Uranium Ban]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_power_plant)|Основа (pmg_base_building_power_plant)]]
- **Методы производства** (replacement_if_valid): [[tr/Методы производства/Nuclear Reactor|Nuclear Reactor]]

---
type: concept
description: "Метод производства «Heavy Machineries (pm_heavy_machineries_building_uranium_mine)» — T&R 1.13, `pm_heavy_machineries_building_uranium_mine`"
project: vic3
source: tr
aliases: ["Heavy Machineries (pm_heavy_machineries_building_uranium_mine)", "Heavy Machineries", "pm_heavy_machineries_building_uranium_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_heavy_machineries_building_uranium_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Heavy Machineries (pm_heavy_machineries_building_uranium_mine)

Метод производства · `pm_heavy_machineries_building_uranium_mine` · `common/production_methods/ztr_new_production_methods.txt:2744`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/advanced_mining_systems.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `20`
- **unlocking_technologies**: [[tr/Технологии/Heavy Machinery|Heavy Machinery]]
- **building_modifiers**:
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.2`
    - `building_machinists_mortality_mult` = `0.1`
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `3` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_robotics_add` = `7` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_engines_add` = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_good_uranium_add` = `110` → [[tr/Товары/Uranium|Uranium]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining equipment (pmg_curie_mining_equipment_building_uranium_mine)|Mining equipment (pmg_curie_mining_equipment_building_uranium_mine)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/HPGR Comminution (pm_hpgr_comminution)|HPGR Comminution (pm_hpgr_comminution)]]

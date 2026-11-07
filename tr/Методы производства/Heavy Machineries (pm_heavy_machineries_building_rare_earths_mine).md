---
type: concept
description: "Метод производства «Heavy Machineries (pm_heavy_machineries_building_rare_earths_mine)» — T&R 1.13, `pm_heavy_machineries_building_rare_earths_mine`"
project: vic3
source: tr
aliases: ["Heavy Machineries (pm_heavy_machineries_building_rare_earths_mine)", "Heavy Machineries", "pm_heavy_machineries_building_rare_earths_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_heavy_machineries_building_rare_earths_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Heavy Machineries (pm_heavy_machineries_building_rare_earths_mine)

Метод производства · `pm_heavy_machineries_building_rare_earths_mine` · `common/production_methods/ztr_new_production_methods.txt:3418`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/advanced_mining_systems.dds`
- **unlocking_technologies**: [[tr/Технологии/Heavy Machinery|Heavy Machinery]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `60`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_electroniccomponents_add` = `3` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_robotics_add` = `7` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_engines_add` = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_rare_earths_add` = `85` → [[tr/Товары/Rare Earths|Rare Earths]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `4250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.05`
    - `building_machinists_mortality_mult` = `0.05`
    - `building_engineers_mortality_mult` = `0.05`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_rare_earths_mine)|Mining Equipment (pmg_mining_equipment_building_rare_earths_mine)]]

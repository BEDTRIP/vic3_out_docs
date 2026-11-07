---
type: concept
description: "Метод производства «Wind Turbines» — T&R 1.13, `pm_wind_turbines`"
project: vic3
source: tr
aliases: ["Wind Turbines", "pm_wind_turbines"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_wind_turbines
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Wind Turbines

Метод производства · `pm_wind_turbines` · `common/production_methods/ztr_energy_production_methods.txt:1295`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_wind_turbines.dds`
- **unlocking_technologies**: [[tr/Технологии/Wind Turbines|Wind Turbines]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `3` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_batteries_add` = `15` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_alloys_add` = `10` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_rare_earths_add` = `3` → [[tr/Товары/Rare Earths|Rare Earths]]
    - `goods_output_global_electricity_add` = `95` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `900` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Renewable Energy Plant|Renewable Energy Plant]]

---
type: concept
description: "Метод производства «Hydroelectric Turbines» — Hail Columbia 1.13, `pm_usfp_hoover_dam`"
project: vic3
source: hail_columbia
aliases: ["Hydroelectric Turbines", "pm_usfp_hoover_dam"]
tags: [hail_columbia, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_usfp_hoover_dam
paths: [for addon/Hail Columbia/common/production_methods/usfp_production_methods.txt]
---
# Hydroelectric Turbines

Метод производства · `pm_usfp_hoover_dam` · `common/production_methods/usfp_production_methods.txt:265`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/hydroelectric_plant.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_engines_add` = `50` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_electricity_add` = `400` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `600` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `200` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[hail_columbia/Группы методов/Boulder Dam|Boulder Dam]]

---
type: concept
description: "Метод производства «Sail-steamships» — LLWA 1.13, `LLWA_pm_sail_steamboats`"
project: vic3
source: llwa
aliases: ["Sail-steamships", "LLWA_pm_sail_steamboats"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_sail_steamboats
paths: [llwa/common/production_methods/LLWA_water.txt]
---
# Sail-steamships

Метод производства · `LLWA_pm_sail_steamboats` · `common/production_methods/LLWA_water.txt:24`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_sailsteamers.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_clippers_add` = `4` → [[vanilla/Товары/Клипперы|Клипперы]]
    - `goods_input_engines_add` = `2` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_coal_add` = `2` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_transportation_add` = `25` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `600` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `200` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_clerks_add` = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `25`
    - `state_pollution_generation_add` = `20`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_water_base)|Основа (LLWA_pmg_water_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Diesel Ferries|Diesel Ferries]], [[llwa/Методы производства/Packet Boats|Packet Boats]], [[llwa/Методы производства/Steamboats|Steamboats]]

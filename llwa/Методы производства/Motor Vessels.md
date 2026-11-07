---
type: concept
description: "Метод производства «Motor Vessels» — LLWA 1.13, `LLWA_pm_motor_vessels`"
project: vic3
source: llwa
aliases: ["Motor Vessels", "LLWA_pm_motor_vessels"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_motor_vessels
paths: [llwa/common/production_methods/LLWA_water.txt]
---
# Motor Vessels

Метод производства · `LLWA_pm_motor_vessels` · `common/production_methods/LLWA_water.txt:82`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_diesel_ships.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Компрессионное зажигание|Компрессионное зажигание]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_steamers_add` = `4` → [[vanilla/Товары/Пароходы|Пароходы]]
    - `goods_input_oil_add` = `4` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_transportation_add` = `40` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `400` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `300` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `100` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_clerks_add` = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `40`
    - `state_pollution_generation_add` = `10`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_water_base)|Основа (LLWA_pmg_water_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Diesel Ferries|Diesel Ferries]], [[llwa/Методы производства/Packet Boats|Packet Boats]], [[llwa/Методы производства/Steamboats|Steamboats]]

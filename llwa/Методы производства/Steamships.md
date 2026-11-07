---
type: concept
description: "Метод производства «Steamships» — LLWA 1.13, `LLWA_pm_steamboats`"
project: vic3
source: llwa
aliases: ["Steamships", "LLWA_pm_steamboats"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_steamboats
paths: [llwa/common/production_methods/LLWA_water.txt]
---
# Steamships

Метод производства · `LLWA_pm_steamboats` · `common/production_methods/LLWA_water.txt:53`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/reinforced_steam_ships.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Козловые краны|Козловые краны]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_steamers_add` = `4` → [[vanilla/Товары/Пароходы|Пароходы]]
    - `goods_input_coal_add` = `4` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_transportation_add` = `30` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `50` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_clerks_add` = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `30`
    - `state_pollution_generation_add` = `15`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Основа (LLWA_pmg_water_base)|Основа (LLWA_pmg_water_base)]]
- **Методы производства** (unlocking_production_methods): [[llwa/Методы производства/Diesel Ferries|Diesel Ferries]], [[llwa/Методы производства/Packet Boats|Packet Boats]], [[llwa/Методы производства/Steamboats|Steamboats]]

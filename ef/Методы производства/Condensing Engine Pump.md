---
type: concept
description: "Метод производства «Condensing Engine Pump» — E&F 1.13, `pm_condensing_engine_pump_building_silver_mine`"
project: vic3
source: ef
aliases: ["Condensing Engine Pump", "pm_condensing_engine_pump_building_silver_mine"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_condensing_engine_pump_building_silver_mine
paths: [E&F/common/production_methods/03_ef_mines.txt]
---
# Condensing Engine Pump

Метод производства · `pm_condensing_engine_pump_building_silver_mine` · `common/production_methods/03_ef_mines.txt:112`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/condensing_engine_pump.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_silver_add` = `60` → [[ef/Товары/Silver|Silver]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Mining Equipment|Mining Equipment]]

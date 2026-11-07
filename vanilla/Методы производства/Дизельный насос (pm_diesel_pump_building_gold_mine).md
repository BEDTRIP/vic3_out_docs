---
type: concept
description: "Метод производства «Дизельный насос (pm_diesel_pump_building_gold_mine)» — ваниль 1.13, `pm_diesel_pump_building_gold_mine`"
project: vic3
source: vanilla
aliases: ["Дизельный насос (pm_diesel_pump_building_gold_mine)", "Diesel Pump", "pm_diesel_pump_building_gold_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_diesel_pump_building_gold_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Дизельный насос (pm_diesel_pump_building_gold_mine)

Метод производства · `pm_diesel_pump_building_gold_mine` · `common/production_methods/03_mines.txt:886`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/diesel_pump.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Компрессионное зажигание|Компрессионное зажигание]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_oil_add` = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_output_gold_add` = `30` → [[vanilla/Товары/Золото|Золото]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_minting_add` = `1000`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Горнодобывающее оборудование (pmg_mining_equipment_building_gold_mine)|Горнодобывающее оборудование (pmg_mining_equipment_building_gold_mine)]]

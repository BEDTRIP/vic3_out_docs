---
type: concept
description: "Метод производства «Дизельный насос (pm_diesel_pump_building_lead_mine)» — ваниль 1.13, `pm_diesel_pump_building_lead_mine`"
project: vic3
source: vanilla
aliases: ["Дизельный насос (pm_diesel_pump_building_lead_mine)", "Diesel Pump", "pm_diesel_pump_building_lead_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_diesel_pump_building_lead_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Дизельный насос (pm_diesel_pump_building_lead_mine)

Метод производства · `pm_diesel_pump_building_lead_mine` · `common/production_methods/03_mines.txt:525`

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
    - `goods_output_lead_add` = `70` → [[vanilla/Товары/Свинец|Свинец]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Горнодобывающее оборудование (pmg_mining_equipment_building_lead_mine)|Горнодобывающее оборудование (pmg_mining_equipment_building_lead_mine)]]

---
type: concept
description: "Метод производства «Паровой насос с конденсатором (pm_condensing_engine_pump_building_sulfur_mine)» — ваниль 1.13, `pm_condensing_engine_pump_building_sulfur_mine`"
project: vic3
source: vanilla
aliases: ["Паровой насос с конденсатором (pm_condensing_engine_pump_building_sulfur_mine)", "Condensing Engine Pump", "pm_condensing_engine_pump_building_sulfur_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_condensing_engine_pump_building_sulfur_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Паровой насос с конденсатором (pm_condensing_engine_pump_building_sulfur_mine)

Метод производства · `pm_condensing_engine_pump_building_sulfur_mine` · `common/production_methods/03_mines.txt:665`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/condensing_engine_pump.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `15`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `15` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_sulfur_add` = `60` → [[vanilla/Товары/Сера|Сера]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Горнодобывающее оборудование (pmg_mining_equipment_building_sulfur_mine)|Горнодобывающее оборудование (pmg_mining_equipment_building_sulfur_mine)]]

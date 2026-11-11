---
type: concept
description: "Метод производства «Пароатмосферный насос (pm_atmospheric_engine_pump_building_gold_mine)» — ваниль 1.15, `pm_atmospheric_engine_pump_building_gold_mine`"
project: vic3
audience: agent
source: vanilla
aliases: ["Пароатмосферный насос (pm_atmospheric_engine_pump_building_gold_mine)", "Atmospheric Engine Pump", "pm_atmospheric_engine_pump_building_gold_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_atmospheric_engine_pump_building_gold_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Пароатмосферный насос (pm_atmospheric_engine_pump_building_gold_mine)

Метод производства · `pm_atmospheric_engine_pump_building_gold_mine` · `common/production_methods/03_mines.txt:812`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pumps.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Пароатмосферный двигатель|Пароатмосферный двигатель]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `10` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-gold-add|goods_output_gold_add]] = `15` → [[vanilla/Товары/Золото|Золото]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-minting-add|country_minting_add]] = `500`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Горнодобывающее оборудование (pmg_mining_equipment_building_gold_mine)|Горнодобывающее оборудование (pmg_mining_equipment_building_gold_mine)]]

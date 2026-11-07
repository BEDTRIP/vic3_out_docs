---
type: concept
description: "Метод производства «Diesel Pump» — E&F 1.13, `pm_diesel_pump_building_silver_mine`"
project: vic3
source: ef
aliases: ["Diesel Pump", "pm_diesel_pump_building_silver_mine"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_diesel_pump_building_silver_mine
paths: [E&F/common/production_methods/03_ef_mines.txt]
---
# Diesel Pump

Метод производства · `pm_diesel_pump_building_silver_mine` · `common/production_methods/03_ef_mines.txt:143`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/diesel_pump.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Компрессионное зажигание|Компрессионное зажигание]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-silver-add|goods_output_silver_add]] = `90` → [[ef/Товары/Silver|Silver]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[ef/Группы методов/Mining Equipment|Mining Equipment]]

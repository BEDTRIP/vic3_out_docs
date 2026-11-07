---
type: concept
description: "Метод производства «Дизельный насос (pm_diesel_pump_building_sulfur_mine)» — ваниль 1.13, `pm_diesel_pump_building_sulfur_mine`"
project: vic3
audience: agent
source: vanilla
aliases: ["Дизельный насос (pm_diesel_pump_building_sulfur_mine)", "Diesel Pump", "pm_diesel_pump_building_sulfur_mine"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_diesel_pump_building_sulfur_mine
paths: [.vanillaVIC3/common/production_methods/03_mines.txt]
---
# Дизельный насос (pm_diesel_pump_building_sulfur_mine)

Метод производства · `pm_diesel_pump_building_sulfur_mine` · `common/production_methods/03_mines.txt:696`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/diesel_pump.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Компрессионное зажигание|Компрессионное зажигание]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-sulfur-add|goods_output_sulfur_add]] = `80` → [[vanilla/Товары/Сера|Сера]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Горнодобывающее оборудование (pmg_mining_equipment_building_sulfur_mine)|Горнодобывающее оборудование (pmg_mining_equipment_building_sulfur_mine)]]

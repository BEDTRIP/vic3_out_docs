---
type: concept
description: "Метод производства «Дизельный насос (pm_diesel_pump_building_gold_mine)» — T&R 1.13, `pm_diesel_pump_building_gold_mine`"
project: vic3
audience: agent
source: tr
aliases: ["Дизельный насос (pm_diesel_pump_building_gold_mine)", "Diesel Pump", "pm_diesel_pump_building_gold_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_diesel_pump_building_gold_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_vanilla_production_methods.txt]
replaces: "[[vanilla/Методы производства/Дизельный насос (pm_diesel_pump_building_gold_mine)]]"
---
# Дизельный насос (pm_diesel_pump_building_gold_mine)

Метод производства · `pm_diesel_pump_building_gold_mine` · `common/production_methods/ztr_vanilla_production_methods.txt:1760` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **state_modifiers**: изменено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/diesel_pump.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `15`
- **unlocking_technologies**: [[vanilla/Технологии/Компрессионное зажигание|Компрессионное зажигание]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_light_fuel_add` = `3` → [[tr/Товары/Light Fuel|Light Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-gold-add|goods_output_gold_add]] = `30` → [[vanilla/Товары/Золото|Золото]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-minting-add|country_minting_add]] = `1000`

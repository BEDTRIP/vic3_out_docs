---
type: concept
description: "Метод производства «Fuel Trawlers» — T&R 1.13, `pm_fuel_trawlers`"
project: vic3
audience: agent
source: tr
aliases: ["Fuel Trawlers", "pm_fuel_trawlers"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_fuel_trawlers
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Fuel Trawlers

Метод производства · `pm_fuel_trawlers` · `common/production_methods/ztr_new_production_methods.txt:9059`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_fuel_trawlers.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/Naval Oil Propulsion|Naval Oil Propulsion]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steamers-add|goods_input_steamers_add]] = `10` → [[vanilla/Товары/Пароходы|Пароходы]]
    - `goods_input_heavy_fuel_add` = `5` → [[tr/Товары/Heavy Fuel|Heavy Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fish-add|goods_output_fish_add]] = `120` → [[vanilla/Товары/Рыба|Рыба]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `750` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `400` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_fishing_wharf)|Основа (pmg_base_building_fishing_wharf)]]

---
type: concept
description: "Метод производства «Дизельный насос (pm_diesel_pump_building_lead_mine)» — T&R 1.13, `pm_diesel_pump_building_lead_mine`"
project: vic3
source: tr
aliases: ["Дизельный насос (pm_diesel_pump_building_lead_mine)", "Diesel Pump", "pm_diesel_pump_building_lead_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_diesel_pump_building_lead_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_vanilla_production_methods.txt]
replaces: "[[vanilla/Методы производства/Дизельный насос (pm_diesel_pump_building_lead_mine)]]"
---
# Дизельный насос (pm_diesel_pump_building_lead_mine)

Метод производства · `pm_diesel_pump_building_lead_mine` · `common/production_methods/ztr_vanilla_production_methods.txt:1698` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **state_modifiers**: изменено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/diesel_pump.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `15`
- **unlocking_technologies**: [[vanilla/Технологии/Компрессионное зажигание|Компрессионное зажигание]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `20` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_light_fuel_add` = `3` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_lead_add` = `70` → [[vanilla/Товары/Свинец|Свинец]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `2250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]

---
type: concept
description: "Метод производства «Atmospheric Engine Pump (pm_atmospheric_engine_pump_building_copper_mine)» — T&R 1.13, `pm_atmospheric_engine_pump_building_copper_mine`"
project: vic3
source: tr
aliases: ["Atmospheric Engine Pump (pm_atmospheric_engine_pump_building_copper_mine)", "Atmospheric Engine Pump", "pm_atmospheric_engine_pump_building_copper_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_atmospheric_engine_pump_building_copper_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Atmospheric Engine Pump (pm_atmospheric_engine_pump_building_copper_mine)

Метод производства · `pm_atmospheric_engine_pump_building_copper_mine` · `common/production_methods/ztr_new_production_methods.txt:4901`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pumps.dds`
- **unlocking_technologies**: [[tr/Технологии/Пароатмосферный двигатель|Пароатмосферный двигатель]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `10` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_copper_add` = `40` → [[tr/Товары/Copper|Copper]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_laborers_add` = `3750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining Equipment (pmg_mining_equipment_building_copper_mine)|Mining Equipment (pmg_mining_equipment_building_copper_mine)]]

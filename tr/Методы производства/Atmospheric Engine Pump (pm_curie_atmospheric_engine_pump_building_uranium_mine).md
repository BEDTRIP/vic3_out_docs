---
type: concept
description: "Метод производства «Atmospheric Engine Pump (pm_curie_atmospheric_engine_pump_building_uranium_mine)» — T&R 1.13, `pm_curie_atmospheric_engine_pump_building_uranium_mine`"
project: vic3
source: tr
aliases: ["Atmospheric Engine Pump (pm_curie_atmospheric_engine_pump_building_uranium_mine)", "Atmospheric Engine Pump", "pm_curie_atmospheric_engine_pump_building_uranium_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_curie_atmospheric_engine_pump_building_uranium_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Atmospheric Engine Pump (pm_curie_atmospheric_engine_pump_building_uranium_mine)

Метод производства · `pm_curie_atmospheric_engine_pump_building_uranium_mine` · `common/production_methods/ztr_modified_mr_production_methods.txt:920`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pumps.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[tr/Технологии/Пароатмосферный двигатель|Пароатмосферный двигатель]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `10` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_good_uranium_add` = `40` → [[tr/Товары/Uranium|Uranium]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_laborers_add` = `3750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.2`
    - `building_machinists_mortality_mult` = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining equipment (pmg_curie_mining_equipment_building_uranium_mine)|Mining equipment (pmg_curie_mining_equipment_building_uranium_mine)]]

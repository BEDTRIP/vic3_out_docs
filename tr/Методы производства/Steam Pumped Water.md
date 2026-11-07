---
type: concept
description: "Метод производства «Steam Pumped Water» — T&R 1.13, `pm_steam_pumped_water`"
project: vic3
source: tr
aliases: ["Steam Pumped Water", "pm_steam_pumped_water"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_steam_pumped_water
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Steam Pumped Water

Метод производства · `pm_steam_pumped_water` · `common/production_methods/ztr_new_production_methods.txt:6395`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_steam_pumped_water.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Паровик|Паровик]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `4`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_tools_add` = `30` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_coal_add` = `15` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_input_engines_add` = `15` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_water_add` = `75` → [[tr/Товары/Water|Water]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `600` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `300` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Water|Water]]

---
type: concept
description: "Метод производства «Advanced Refining» — T&R 1.13, `pm_advanced_purification_mine`"
project: vic3
source: tr
aliases: ["Advanced Refining", "pm_advanced_purification_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_purification_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Refining

Метод производства · `pm_advanced_purification_mine` · `common/production_methods/ztr_new_production_methods.txt:8483`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/purification_mine.dds`
- **unlocking_technologies**: [[tr/Технологии/Rare Earths Purification|Rare Earths Purification]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `50`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fertilizer_add` = `60` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_robotics_add` = `15` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_steel_add` = `15` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_output_rare_earths_add` = `25` → [[tr/Товары/Rare Earths|Rare Earths]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_laborers_add` = `-3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Steam Automation (pmg_steam_automation_building_rare_earths_mine)|Steam Automation (pmg_steam_automation_building_rare_earths_mine)]]

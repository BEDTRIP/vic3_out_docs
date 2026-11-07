---
type: concept
description: "Метод производства «Modern Tools» — T&R 1.13, `pm_modern_tools`"
project: vic3
source: tr
aliases: ["Modern Tools", "pm_modern_tools"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_modern_tools
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Modern Tools

Метод производства · `pm_modern_tools` · `common/production_methods/ztr_new_production_methods.txt:6317`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_modern_tools.dds`
- **unlocking_technologies**: [[tr/Технологии/Modern Tools|Modern Tools]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_rubber_add` = `10` → [[vanilla/Товары/Каучук|Каучук]]
    - `goods_input_copperwires_add` = `3` → [[tr/Товары/Wires|Wires]]
    - `goods_input_alloys_add` = `5` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_steel_add` = `15` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_output_tools_add` = `125` → [[vanilla/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_laborers_add` = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_tooling_workshop)|Основа (pmg_base_building_tooling_workshop)]]

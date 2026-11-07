---
type: concept
description: "Метод производства «Modern Urban Utilities» — T&R 1.13, `pm_modern_urban_utilities`"
project: vic3
source: tr
aliases: ["Modern Urban Utilities", "pm_modern_urban_utilities"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_modern_urban_utilities
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Modern Urban Utilities

Метод производства · `pm_modern_urban_utilities` · `common/production_methods/ztr_new_production_methods.txt:6870`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_modern_urban_utilities.dds`
- **city_lights_color_index**: `2`
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-mortality-mult|state_mortality_mult]] = `-0.01`
- **unlocking_technologies**: [[tr/Технологии/Basic Appliances|Basic Appliances]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_alloys_add` = `0.5` → [[tr/Товары/Alloys|Alloys]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_copperwires_add` = `2` → [[tr/Товары/Wires|Wires]]
    - `goods_input_telecommunications_add` = `3` → [[tr/Товары/Telecommunications|Telecommunications]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `25` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `50` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `100` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `3`
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Уличное освещение|Уличное освещение]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Waste Incinerator|Waste Incinerator]]

---
type: concept
description: "Метод производства «Private Charters» — T&R 1.13, `pm_private_charters`"
project: vic3
source: tr
aliases: ["Private Charters", "pm_private_charters"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_private_charters
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Private Charters

Метод производства · `pm_private_charters` · `common/production_methods/ztr_modified_mr_production_methods.txt:490`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/air_travel_1.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_civil_planes_add` = `4` → [[tr/Товары/Airplanes|Airplanes]]
    - `goods_input_electricity_add` = `3` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_telephones_add` = `2` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_output_transportation_add` = `50` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_clerks_add` = `250` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `10`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Flight Type|Flight Type]]

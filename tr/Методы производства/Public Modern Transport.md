---
type: concept
description: "Метод производства «Public Modern Transport» — T&R 1.13, `pm_modern_city_transport`"
project: vic3
source: tr
aliases: ["Public Modern Transport", "pm_modern_city_transport"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_modern_city_transport
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Public Modern Transport

Метод производства · `pm_modern_city_transport` · `common/production_methods/ztr_new_production_methods.txt:6813`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_modern_city_transport.dds`
- **unlocking_technologies**: [[tr/Технологии/Modern City Transport|Modern City Transport]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `8`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_automobiles_add` = `1` → [[tr/Товары/Автомобили|Автомобили]]
    - `goods_input_electricity_add` = `0.5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_transportation_add` = `8` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_engineers_add` = `150` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_machinists_add` = `250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_laborers_add` = `-1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Общественный транспорт|Общественный транспорт]]

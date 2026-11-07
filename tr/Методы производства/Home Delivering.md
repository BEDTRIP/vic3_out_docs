---
type: concept
description: "Метод производства «Home Delivering» — T&R 1.13, `pm_delivering_bakery`"
project: vic3
source: tr
aliases: ["Home Delivering", "pm_delivering_bakery"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_delivering_bakery
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Home Delivering

Метод производства · `pm_delivering_bakery` · `common/production_methods/ztr_new_production_methods.txt:589`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/bike_scooter_transportation.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `2`
- **unlocking_technologies**: [[tr/Технологии/Home Delivery Networks|Home Delivery Networks]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_transportation_add` = `6` → [[vanilla/Товары/Перевозка|Перевозка]]
    - `goods_input_automobiles_add` = `2` → [[tr/Товары/Автомобили|Автомобили]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `-250` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Transport (pmg_delivery_building_food_industry)|Transport (pmg_delivery_building_food_industry)]]

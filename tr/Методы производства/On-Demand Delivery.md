---
type: concept
description: "Метод производства «On-Demand Delivery» — T&R 1.13, `pm_delivering_on_demand_bakery`"
project: vic3
source: tr
aliases: ["On-Demand Delivery", "pm_delivering_on_demand_bakery"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_delivering_on_demand_bakery
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# On-Demand Delivery

Метод производства · `pm_delivering_on_demand_bakery` · `common/production_methods/ztr_new_production_methods.txt:615`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_multiway_transport_building.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `2`
- **unlocking_technologies**: [[tr/Технологии/On-Demand Delivery|On-Demand Delivery]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_on_demand_goods_add` = `6` → [[tr/Товары/On-Demand Goods|On-Demand Goods]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `-500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_shopkeepers_add` = `-250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Transport (pmg_delivery_building_food_industry)|Transport (pmg_delivery_building_food_industry)]]

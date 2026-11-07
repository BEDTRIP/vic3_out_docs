---
type: concept
description: "Метод производства «Platform Gig Delivery» — T&R 1.13, `pm_platform_gig_delivery`"
project: vic3
source: tr
aliases: ["Platform Gig Delivery", "pm_platform_gig_delivery"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_platform_gig_delivery
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Platform Gig Delivery

Метод производства · `pm_platform_gig_delivery` · `common/production_methods/ztr_data_production_methods.txt:890`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_platform_gig_delivery.dds`
- **unlocking_technologies**: [[tr/Технологии/Freight Villages|Freight Villages]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `5` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `5` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_computer_add` = `4` → [[tr/Товары/Computers|Computers]]
    - `goods_output_on_demand_goods_add` = `85` → [[tr/Товары/On-Demand Goods|On-Demand Goods]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `500` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Delivery Mode|Delivery Mode]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Heavy Centralized Fulfilment|Heavy Centralized Fulfilment]]

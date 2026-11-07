---
type: concept
description: "Метод производства «Local Courier Network» — T&R 1.13, `pm_local_courier_network`"
project: vic3
audience: agent
source: tr
aliases: ["Local Courier Network", "pm_local_courier_network"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_local_courier_network
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Local Courier Network

Метод производства · `pm_local_courier_network` · `common/production_methods/ztr_data_production_methods.txt:868`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/local_courier_network.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_robotics_add` = `3` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `5` → [[vanilla/Товары/Телефоны|Телефоны]]
    - `goods_input_electroniccomponents_add` = `3` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_output_on_demand_goods_add` = `65` → [[tr/Товары/On-Demand Goods|On-Demand Goods]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `500` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Delivery Mode|Delivery Mode]]

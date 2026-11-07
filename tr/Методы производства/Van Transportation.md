---
type: concept
description: "Метод производства «Van Transportation» — T&R 1.13, `pm_truck_van_transportation`"
project: vic3
source: tr
aliases: ["Van Transportation", "pm_truck_van_transportation"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_truck_van_transportation
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Van Transportation

Метод производства · `pm_truck_van_transportation` · `common/production_methods/ztr_data_production_methods.txt:1064`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_truck_van_transportation.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_automobiles_add` = `3` → [[tr/Товары/Автомобили|Автомобили]]
    - `goods_input_transportation_add` = `20` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `-250` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Transport (pmg_transport_building_ecommerce_logistics)|Transport (pmg_transport_building_ecommerce_logistics)]]

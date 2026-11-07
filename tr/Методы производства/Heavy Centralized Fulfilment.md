---
type: concept
description: "Метод производства «Heavy Centralized Fulfilment» — T&R 1.13, `pm_heavy_centralized_fulfilment`"
project: vic3
audience: agent
source: tr
aliases: ["Heavy Centralized Fulfilment", "pm_heavy_centralized_fulfilment"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_heavy_centralized_fulfilment
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Heavy Centralized Fulfilment

Метод производства · `pm_heavy_centralized_fulfilment` · `common/production_methods/ztr_data_production_methods.txt:981`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/centralized_fulfilment_centers.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_homeappliances_add` = `2` → [[tr/Товары/Home Appliances|Home Appliances]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-furniture-add|goods_input_furniture_add]] = `2` → [[vanilla/Товары/Мебель|Мебель]]
    - `goods_input_computer_add` = `2` → [[tr/Товары/Computers|Computers]]
    - `goods_input_televisions_add` = `2` → [[tr/Товары/Televisions|Televisions]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `4` → [[vanilla/Товары/Телефоны|Телефоны]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `-100` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-150` → [[vanilla/Население/Типы/Механики|Механики]]
- **unlocking_production_methods**: [[tr/Методы производства/Platform Gig Delivery|Platform Gig Delivery]], [[tr/Методы производства/Integrated Retail E-Commerce|Integrated Retail E-Commerce]], [[tr/Методы производства/Predictive Fulfilment Network|Predictive Fulfilment Network]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Fulfilment Type|Fulfilment Type]]

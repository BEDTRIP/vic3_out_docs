---
type: concept
description: "Метод производства «Freight» — T&R 1.13, `pm_air_freight`"
project: vic3
audience: agent
source: tr
aliases: ["Freight", "pm_air_freight"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_air_freight
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Freight

Метод производства · `pm_air_freight` · `common/production_methods/ztr_modified_mr_production_methods.txt:650`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/air_freight.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `5` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `5` → [[vanilla/Товары/Услуги|Услуги]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `20` → [[vanilla/Товары/Перевозка|Перевозка]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-merchant-marine-add|goods_output_merchant_marine_add]] = `2` → [[vanilla/Товары/Торговые корабли|Торговые корабли]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `150` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `2`
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Cargo Type|Cargo Type]]

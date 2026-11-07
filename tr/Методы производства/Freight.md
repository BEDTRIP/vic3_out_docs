---
type: concept
description: "Метод производства «Freight» — T&R 1.13, `pm_air_freight`"
project: vic3
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
    - `goods_input_paper_add` = `5` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_light_fuel_add` = `5` → [[tr/Товары/Light Fuel|Light Fuel]]
    - `goods_output_services_add` = `5` → [[vanilla/Товары/Услуги|Услуги]]
    - `goods_output_transportation_add` = `20` → [[vanilla/Товары/Перевозка|Перевозка]]
    - `goods_output_merchant_marine_add` = `2` → [[vanilla/Товары/Торговые корабли|Торговые корабли]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `150` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_clerks_add` = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `2`
    - `state_pollution_generation_add` = `10`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Cargo Type|Cargo Type]]

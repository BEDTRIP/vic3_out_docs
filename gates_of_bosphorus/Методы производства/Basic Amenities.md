---
type: concept
description: "Метод производства «Basic Amenities» — Gates of Bosphorus 1.13, `pm_gbbf_basic_amenities`"
project: vic3
source: gates_of_bosphorus
aliases: ["Basic Amenities", "pm_gbbf_basic_amenities"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_basic_amenities
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Basic Amenities

Метод производства · `pm_gbbf_basic_amenities` · `common/production_methods/gbbf_08_monuments_methods.txt:268`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_basic_amenities.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_migration_pull_mult` = `0.05`
    - `state_loyalism_increases_full_acceptance_mult` = `0.05`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_groceries_add` = `10` → [[vanilla/Товары/Продукты|Продукты]]
    - `goods_input_liquor_add` = `5` → [[vanilla/Товары/Спирт|Спирт]]
    - `goods_output_services_add` = `50` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_shopkeepers_add` = `200` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Track Amenities|Track Amenities]]

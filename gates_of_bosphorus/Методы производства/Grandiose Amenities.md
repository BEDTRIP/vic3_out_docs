---
type: concept
description: "Метод производства «Grandiose Amenities» — Gates of Bosphorus 1.13, `pm_gbbf_grandiose_amenities`"
project: vic3
source: gates_of_bosphorus
aliases: ["Grandiose Amenities", "pm_gbbf_grandiose_amenities"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_grandiose_amenities
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Grandiose Amenities

Метод производства · `pm_gbbf_grandiose_amenities` · `common/production_methods/gbbf_08_monuments_methods.txt:313`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_grandiose_amenities.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_migration_pull_mult` = `0.15`
    - `state_loyalism_increases_full_acceptance_mult` = `0.15`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_groceries_add` = `40` → [[vanilla/Товары/Продукты|Продукты]]
    - `goods_input_liquor_add` = `20` → [[vanilla/Товары/Спирт|Спирт]]
    - `goods_input_tobacco_add` = `15` → [[vanilla/Товары/Табак|Табак]]
    - `goods_input_electricity_add` = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_services_add` = `100` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `250` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_shopkeepers_add` = `750` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Track Amenities|Track Amenities]]

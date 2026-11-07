---
type: concept
description: "Метод производства «Grandiose Amenities» — Gates of Bosphorus 1.13, `pm_gbbf_grandiose_amenities`"
project: vic3
audience: agent
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
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.15`
    - [[vanilla/движок/Модификаторы S#^m-state-loyalism-increases-full-acceptance-mult|state_loyalism_increases_full_acceptance_mult]] = `0.15`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-groceries-add|goods_input_groceries_add]] = `40` → [[vanilla/Товары/Продукты|Продукты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-liquor-add|goods_input_liquor_add]] = `20` → [[vanilla/Товары/Спирт|Спирт]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tobacco-add|goods_input_tobacco_add]] = `15` → [[vanilla/Товары/Табак|Табак]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `100` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `250` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `750` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Track Amenities|Track Amenities]]

---
type: concept
description: "Метод производства «Adequate Amenities» — Gates of Bosphorus 1.13, `pm_gbbf_adequate_amenities`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Adequate Amenities", "pm_gbbf_adequate_amenities"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_adequate_amenities
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Adequate Amenities

Метод производства · `pm_gbbf_adequate_amenities` · `common/production_methods/gbbf_08_monuments_methods.txt:290`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_adequate_amenities.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.10`
    - [[vanilla/движок/Модификаторы S#^m-state-loyalism-increases-full-acceptance-mult|state_loyalism_increases_full_acceptance_mult]] = `0.10`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-groceries-add|goods_input_groceries_add]] = `20` → [[vanilla/Товары/Продукты|Продукты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-liquor-add|goods_input_liquor_add]] = `10` → [[vanilla/Товары/Спирт|Спирт]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tobacco-add|goods_input_tobacco_add]] = `5` → [[vanilla/Товары/Табак|Табак]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `75` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `400` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Track Amenities|Track Amenities]]

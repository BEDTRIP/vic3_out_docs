---
type: concept
description: "Метод производства «Memorialized Administrative Center» — Gates of Bosphorus 1.13, `pm_gbbf_topkapi_palace_museum`"
project: vic3
source: gates_of_bosphorus
aliases: ["Memorialized Administrative Center", "pm_gbbf_topkapi_palace_museum"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_topkapi_palace_museum
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Memorialized Administrative Center

Метод производства · `pm_gbbf_topkapi_palace_museum` · `common/production_methods/gbbf_08_monuments_methods.txt:431`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_museum_building.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `10`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-migration-pull-mult|state_migration_pull_mult]] = `0.5`
    - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.05`
- **building_modifiers**:
  - **workforce_scaled**: пусто
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `500` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `4000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **unlocking_production_methods**: `pm_gbbf_topkapi_palace_museum`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Topkapı Palace|Topkapı Palace]]

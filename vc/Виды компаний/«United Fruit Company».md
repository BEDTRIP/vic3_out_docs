---
type: concept
description: "Вид компании ««United Fruit Company»» — VC 1.13, `company_united_fruit`"
project: vic3
source: vc
aliases: ["«United Fruit Company»", "United Fruit Company", "company_united_fruit"]
tags: [VC, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_united_fruit
paths: [VC/common/company_types/joi_companies.txt]
replaces: "[[vanilla/Виды компаний/«United Fruit Company»]]"
---
# «United Fruit Company»

Вид компании · `company_united_fruit` · `common/company_types/joi_companies.txt:685`

## Отличия от ваниль

- **building_types**: изменено
- **extension_building_types**: изменено
- **prosperity_modifier**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_united_fruit_co.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOUISIANA`
- **building_types**: [[vc/Здания/Банановые плантации|Банановые плантации]], [[vc/Здания/Плантации сахарного тростника|Плантации сахарного тростника]], [[vc/Здания/Маисовые поля|Маисовые поля]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: [[vc/Здания/Пищевые производства|Пищевые производства]]
- **possible_prestige_goods**: `prestige_good_gros_michel_banana`
- **potential**: скрипт, строки 708–713
- **possible**: скрипт, строки 715–733
- **prosperity_modifier**:
  - `building_group_bg_plantations_throughput_add` = `0.1`
  - `state_working_adult_ratio_add` = `0.025`
  - `goods_output_fruit_mult` = `0.25` → [[vanilla/Товары/Фрукты|Фрукты]]
- **ai_will_do**: скрипт, строки 741–760
- **ai_construction_targets**: скрипт, строки 762–778
- **ai_weight**: скрипт, строки 780–782

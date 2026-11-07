---
type: concept
description: "Вид компании ««United Fruit Company»» — ваниль 1.13, `company_united_fruit`"
project: vic3
source: vanilla
aliases: ["«United Fruit Company»", "United Fruit Company", "company_united_fruit"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_united_fruit
paths: [.vanillaVIC3/common/company_types/00_companies_usa.txt]
---
# «United Fruit Company»

Вид компании · `company_united_fruit` · `common/company_types/00_companies_usa.txt:70`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_united_fruit_co.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOUISIANA`
- **building_types**: [[vanilla/Здания/Плантации сахарного тростника|Плантации сахарного тростника]], [[vanilla/Здания/Банановые плантации|Банановые плантации]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **possible_prestige_goods**: `prestige_good_gros_michel_banana`
- **potential**: скрипт, строки 91–96
- **possible**: скрипт, строки 98–116
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-plantations-throughput-add|building_group_bg_plantations_throughput_add]] = `0.2`
  - [[vanilla/движок/Модификаторы C#^m-country-infamy-decay-mult|country_infamy_decay_mult]] = `-0.25`
- **ai_will_do**: скрипт, строки 123–142
- **ai_construction_targets**: скрипт, строки 144–160
- **ai_weight**: скрипт, строки 162–164

---
type: concept
description: "Вид компании «Samsung» — T&R 1.13, `company_samsung`"
project: vic3
audience: agent
source: tr
aliases: ["Samsung", "company_samsung"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_samsung
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# Samsung

Вид компании · `company_samsung` · `common/company_types/ztr_tech_companies.txt:87`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/south_korea_samsung.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SEOUL`
- **building_types**: [[tr/Здания/Electronic Components Industries|Electronic Components Industries]], [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]], [[tr/Здания/Электрозаводы|Электрозаводы]]
- **extension_building_types**: [[tr/Здания/Chip Foundries|Chip Foundries]]
- **possible_prestige_goods**: `prestige_good_smartphones`
- **prestige_goods_trigger**: скрипт, строки 105–110
- **potential**: скрипт, строки 111–113
- **attainable**: скрипт, строки 114–121
- **possible**: скрипт, строки 122–132
- **prosperity_modifier**:
  - `building_software_industry_throughput_add` = `0.1` → [[tr/Здания/Software Industry|Software Industry]]
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pop-attraction-mult|interest_group_ig_industrialists_pop_attraction_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы U#^m-unit-army-defense-mult|unit_army_defense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 139–145
- **ai_construction_targets**: скрипт, строки 146–153
- **ai_weight**: скрипт, строки 154–156

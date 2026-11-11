---
type: concept
description: "Вид компании «Maple & Co» — ваниль 1.15, `company_maple_and_co`"
project: vic3
audience: agent
source: vanilla
aliases: ["Maple & Co", "company_maple_and_co"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_maple_and_co
paths: [.vanillaVIC3/common/company_types/00_companies_mp1.txt]
---
# Maple & Co

Вид компании · `company_maple_and_co` · `common/company_types/00_companies_mp1.txt:841`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_maple_and_co.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOME_COUNTIES`
- **building_types**: [[vanilla/Здания/Мебельные фабрики|Мебельные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_english_upholstery`
- **potential**: скрипт, строки 861–864
- **attainable**: скрипт, строки 866–874
- **possible**: скрипт, строки 876–883
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-government-throughput-add|building_group_bg_government_throughput_add]] = `0.1`
- **ai_will_do**: скрипт, строки 890–895
- **ai_construction_targets**: скрипт, строки 897–904
- **ai_weight**: скрипт, строки 906–908

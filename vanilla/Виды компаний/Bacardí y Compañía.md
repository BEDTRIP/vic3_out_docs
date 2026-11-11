---
type: concept
description: "Вид компании «Bacardí y Compañía» — ваниль 1.15, `company_bacardi`"
project: vic3
audience: agent
source: vanilla
aliases: ["Bacardí y Compañía", "company_bacardi"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_bacardi
paths: [.vanillaVIC3/common/company_types/00_companies_ip4.txt]
---
# Bacardí y Compañía

Вид компании · `company_bacardi` · `common/company_types/00_companies_ip4.txt:714`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_bacardi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]], [[vanilla/Здания/Стеклозаводы|Стеклозаводы]]
- **extension_building_types**: [[vanilla/Здания/Виноградники|Виноградники]]
- **possible_prestige_goods**: `prestige_good_bacardi_rum`
- **potential**: скрипт, строки 733–736
- **attainable**: скрипт, строки 738–744
- **possible**: скрипт, строки 746–752
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-liberty-desire-add|country_liberty_desire_add]] = `0.10`
  - [[vanilla/движок/Модификаторы B#^m-building-art-academy-throughput-add|building_art_academy_throughput_add]] = `0.1` → [[vanilla/Здания/Академии искусств|Академии искусств]]
- **ai_will_do**: скрипт, строки 759–763
- **ai_construction_targets**: скрипт, строки 765–772
- **ai_weight**: скрипт, строки 774–776

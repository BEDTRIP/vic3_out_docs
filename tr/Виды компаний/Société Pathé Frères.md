---
type: concept
description: "Вид компании «Société Pathé Frères» — T&R 1.13, `company_societe_pathe_freres`"
project: vic3
source: tr
aliases: ["Société Pathé Frères", "company_societe_pathe_freres"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_societe_pathe_freres
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_entertainment_companies.txt]
---
# Société Pathé Frères

Вид компании · `company_societe_pathe_freres` · `common/company_types/ztr_entertainment_companies.txt:247`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/societe_pathe_freres.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_cinema.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]]
- **extension_building_types**: [[tr/Здания/Entertainment Areas|Entertainment Areas]], [[tr/Здания/Академии искусств|Академии искусств]]
- **possible_prestige_goods**: `prestige_good_generic_records_and_films`
- **prestige_goods_trigger**: скрипт, строки 265–270
- **potential**: скрипт, строки 271–273
- **attainable**: скрипт, строки 274–281
- **possible**: скрипт, строки 282–292
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-loyalists-from-political-movements-mult|state_loyalists_from_political_movements_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 297–303
- **ai_construction_targets**: скрипт, строки 304–311
- **ai_weight**: скрипт, строки 312–314

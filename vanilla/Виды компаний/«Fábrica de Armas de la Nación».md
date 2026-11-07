---
type: concept
description: "Вид компании ««Fábrica de Armas de la Nación»» — ваниль 1.13, `company_famae`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Fábrica de Armas de la Nación»", "Fábrica de Armas de la Nación", "company_famae"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_famae
paths: [.vanillaVIC3/common/company_types/00_companies_americas.txt]
---
# «Fábrica de Armas de la Nación»

Вид компании · `company_famae` · `common/company_types/00_companies_americas.txt:471`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/chile_fabrica_de_armas_de_la_nacion.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_SANTIAGO`
- **building_types**: [[vanilla/Здания/Оружейные заводы|Оружейные заводы]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]], [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **extension_building_types**: [[vanilla/Здания/Заводы взрывчатки|Заводы взрывчатки]]
- **possible_prestige_goods**: `prestige_good_generic_small_arms`
- **prestige_goods_trigger**: скрипт, строки 493–498
- **potential**: скрипт, строки 500–502
- **attainable**: скрипт, строки 504–510
- **possible**: скрипт, строки 512–522
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-offense-mult|unit_offense_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-steel-mill-throughput-add|building_steel_mill_throughput_add]] = `0.05` → [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **ai_will_do**: скрипт, строки 529–535
- **ai_construction_targets**: скрипт, строки 537–544
- **ai_weight**: скрипт, строки 546–548

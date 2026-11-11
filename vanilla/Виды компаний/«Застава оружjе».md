---
type: concept
description: "Вид компании ««Застава оружjе»» — ваниль 1.15, `company_zastava`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Застава оружjе»", "Zastava oružje", "company_zastava"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_zastava
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Застава оружjе»

Вид компании · `company_zastava` · `common/company_types/00_companies_europe.txt:1519`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/zastava.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WESTERN_SERBIA`
- **building_types**: [[vanilla/Здания/Оружейные заводы|Оружейные заводы]], [[vanilla/Здания/Заводы боеприпасов|Заводы боеприпасов]]
- **extension_building_types**: [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **possible_prestige_goods**: `prestige_good_generic_small_arms`
- **prestige_goods_trigger**: скрипт, строки 1540–1545
- **potential**: скрипт, строки 1547–1549
- **attainable**: скрипт, строки 1551–1557
- **possible**: скрипт, строки 1559–1567
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы U#^m-unit-defense-mult|unit_defense_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы U#^m-unit-recovery-rate-add|unit_recovery_rate_add]] = `0.05`
- **ai_will_do**: скрипт, строки 1574–1580
- **ai_construction_targets**: скрипт, строки 1582–1589
- **ai_weight**: скрипт, строки 1591–1593

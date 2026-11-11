---
type: concept
description: "Вид компании «Ramirez & Cia. (Filhos) Lda» — ваниль 1.15, `company_ramirez`"
project: vic3
audience: agent
source: vanilla
aliases: ["Ramirez & Cia. (Filhos) Lda", "company_ramirez"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ramirez
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Ramirez & Cia. (Filhos) Lda

Вид компании · `company_ramirez` · `common/company_types/00_companies_ep2.txt:543`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_ramirez.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ALENTEJO`
- **building_types**: [[vanilla/Здания/Пищевые производства|Пищевые производства]], [[vanilla/Здания/Рыболовные верфи|Рыболовные верфи]]
- **extension_building_types**: [[vanilla/Здания/Китобойные станции|Китобойные станции]], [[vanilla/Здания/Порты|Порты]]
- **possible_prestige_goods**: `prestige_good_generic_groceries`
- **prestige_goods_trigger**: скрипт, строки 565–570
- **potential**: скрипт, строки 572–575
- **attainable**: скрипт, строки 577–585
- **possible**: скрипт, строки 587–601
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-spread-mult|country_production_tech_spread_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 608–612
- **ai_construction_targets**: скрипт, строки 614–627
- **ai_weight**: скрипт, строки 629–631

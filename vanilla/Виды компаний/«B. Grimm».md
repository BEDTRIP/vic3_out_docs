---
type: concept
description: "Вид компании ««B. Grimm»» — ваниль 1.15, `company_b_grimm`"
project: vic3
audience: agent
source: vanilla
aliases: ["«B. Grimm»", "B.Grimm", "company_b_grimm"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_b_grimm
paths: [.vanillaVIC3/common/company_types/00_companies_asia.txt]
---
# «B. Grimm»

Вид компании · `company_b_grimm` · `common/company_types/00_companies_asia.txt:937`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/thailand_b_grimm.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BANGKOK`
- **building_types**: [[vanilla/Здания/Рисовые поля|Рисовые поля]]
- **extension_building_types**: [[vanilla/Здания/Заводы удобрений|Заводы удобрений]]
- **possible_prestige_goods**: `prestige_good_generic_grain`
- **prestige_goods_trigger**: скрипт, строки 957–962
- **potential**: скрипт, строки 964–966
- **attainable**: скрипт, строки 968–974
- **possible**: скрипт, строки 976–983
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-from-population-mult|state_infrastructure_from_population_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-food-industry-throughput-add|building_food_industry_throughput_add]] = `0.1` → [[vanilla/Здания/Пищевые производства|Пищевые производства]]
- **ai_will_do**: скрипт, строки 990–995
- **ai_construction_targets**: скрипт, строки 997–1004
- **ai_weight**: скрипт, строки 1006–1008

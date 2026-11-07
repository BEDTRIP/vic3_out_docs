---
type: concept
description: "Вид компании «Broken Hill Proprietary Company Ltd» — ваниль 1.13, `company_broken_hill_proprietary_company`"
project: vic3
source: vanilla
aliases: ["Broken Hill Proprietary Company Ltd", "company_broken_hill_proprietary_company"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_broken_hill_proprietary_company
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Broken Hill Proprietary Company Ltd

Вид компании · `company_broken_hill_proprietary_company` · `common/company_types/00_companies_ep2.txt:456`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_broken_hill_proprietary_company.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NEW_SOUTH_WALES`
- **building_types**: [[vanilla/Здания/Золотые рудники|Золотые рудники]], [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]]
- **extension_building_types**: [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]], [[vanilla/Здания/Железные рудники|Железные рудники]]
- **possible_prestige_goods**: пусто
- **prestige_goods_trigger**: пусто
- **potential**: скрипт, строки 481–484
- **attainable**: скрипт, строки 486–494
- **possible**: скрипт, строки 496–509
- **prosperity_modifier**:
  - `country_production_tech_research_speed_mult` = `0.05`
  - `building_lead_mine_throughput_add` = `0.1` → [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]]
- **ai_will_do**: скрипт, строки 516–520
- **ai_construction_targets**: скрипт, строки 522–535
- **ai_weight**: скрипт, строки 537–539

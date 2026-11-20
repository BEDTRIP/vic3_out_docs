---
type: explanation
description: "Вид компании «MALAXA» — ваниль 1.15.2, `company_malaxa`"
project: vic3
audience: agent
source: vanilla
aliases: ["MALAXA", "company_malaxa"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_malaxa
paths: [.vanillaVIC3/common/company_types/00_companies_ip5.txt]
---
# MALAXA

Вид компании · `company_malaxa` · `common/company_types/00_companies_ip5.txt:702`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_malaxa.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WALLACHIA`
- **building_types**: [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]], [[vanilla/Здания/Железные дороги|Железные дороги]], [[vanilla/Здания/Оружейные заводы|Оружейные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 725–730
- **potential**: скрипт, строки 732–734
- **attainable**: скрипт, строки 736–742
- **possible**: скрипт, строки 744–755
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-research-speed-mult|country_production_tech_research_speed_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 762–767
- **ai_construction_targets**: скрипт, строки 769–776
- **ai_weight**: скрипт, строки 778–780

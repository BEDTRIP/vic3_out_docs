---
type: concept
description: "Вид компании «Ewo Hong» — Mandate of Heaven 1.13, `company_ewo_hong`"
project: vic3
audience: agent
source: mandate_of_heaven
aliases: ["Ewo Hong", "company_ewo_hong"]
tags: [mandate_of_heaven, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_ewo_hong
paths: [for addon/Mandate of Heaven/common/company_types/moh_companies_china.txt]
---
# Ewo Hong

Вид компании · `company_ewo_hong` · `common/company_types/moh_companies_china.txt:475`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ewo_hong.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **category**: `bureaucrat_owned`
- **building_types**: [[vanilla/Здания/Чайные плантации|Чайные плантации]]
- **extension_building_types**: [[vanilla/Здания/Стеклозаводы|Стеклозаводы]]
- **preferred_headquarters**: `STATE_GUANGDONG`
- **possible_prestige_goods**: `prestige_good_china_tea`
- **potential**: скрипт, строки 490–492
- **attainable**: скрипт, строки 493–499
- **possible**: скрипт, строки 500–511
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`
  - [[vanilla/движок/Модификаторы S#^m-state-trade-advantage-mult|state_trade_advantage_mult]] = `0.1`
- **ai_weight**: скрипт, строки 516–518
- **ai_construction_targets**: скрипт, строки 519–527
- **ai_will_do**: скрипт, строки 528–534

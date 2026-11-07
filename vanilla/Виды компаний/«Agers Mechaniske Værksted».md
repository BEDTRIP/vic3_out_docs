---
type: concept
description: "Вид компании ««Agers Mechaniske Værksted»» — ваниль 1.13, `company_aker_mek`"
project: vic3
source: vanilla
aliases: ["«Agers Mechaniske Værksted»", "Agers Mechaniske Værksted", "company_aker_mek"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_aker_mek
paths: [.vanillaVIC3/common/company_types/00_companies_europe.txt]
---
# «Agers Mechaniske Værksted»

Вид компании · `company_aker_mek` · `common/company_types/00_companies_europe.txt:801`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_aker_mek.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbuilding.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EASTERN_NORWAY`
- **building_types**: [[vanilla/Здания/верфи|верфи]], [[vanilla/Здания/Моторные заводы|Моторные заводы]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]]
- **potential**: скрипт, строки 818–820
- **attainable**: скрипт, строки 822–828
- **possible**: скрипт, строки 830–840
- **prosperity_modifier**:
  - `country_ship_group_supply_ships_construction_efficiency_add` = `0.15`
  - `building_fishing_wharf_throughput_add` = `0.05` → [[vanilla/Здания/Рыболовные верфи|Рыболовные верфи]]
- **ai_will_do**: скрипт, строки 847–853
- **ai_construction_targets**: скрипт, строки 855–862
- **ai_weight**: скрипт, строки 864–866

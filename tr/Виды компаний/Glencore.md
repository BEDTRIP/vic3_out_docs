---
type: concept
description: "Вид компании «Glencore» — T&R 1.13, `company_Glencore`"
project: vic3
source: tr
aliases: ["Glencore", "company_Glencore"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_Glencore
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_mining_companies.txt]
---
# Glencore

Вид компании · `company_Glencore` · `common/company_types/ztr_mining_companies.txt:518`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/swizerland_glencore.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_WEST_SWITZERLAND`, `STATE_EAST_SWITZERLAND`
- **building_types**: [[tr/Здания/Rare Earths Mines|Rare Earths Mines]], [[tr/Здания/Copper Mines|Copper Mines]], [[vanilla/Здания/Золотые рудники|Золотые рудники]]
- **extension_building_types**: [[tr/Здания/Буровые вышки|Буровые вышки]], [[tr/Здания/Natural Gas Rigs|Natural Gas Rigs]]
- **potential**: скрипт, строки 535–537
- **attainable**: скрипт, строки 538–549
- **possible**: скрипт, строки 550–563
- **prosperity_modifier**:
  - `building_battery_plant_throughput_add` = `0.1` → [[tr/Здания/Battery Plants|Battery Plants]]
  - `state_market_access_price_impact` = `0.05`
- **ai_will_do**: скрипт, строки 568–576
- **ai_construction_targets**: скрипт, строки 577–595
- **ai_weight**: скрипт, строки 596–598

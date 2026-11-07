---
type: concept
description: "Вид компании «Apple» — T&R 1.13, `company_apple`"
project: vic3
source: tr
aliases: ["Apple", "company_apple"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_apple
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# Apple

Вид компании · `company_apple` · `common/company_types/ztr_tech_companies.txt:20`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_apple.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CALIFORNIA`
- **building_types**: [[tr/Здания/Электрозаводы|Электрозаводы]], [[tr/Здания/Computer Assembly Plants|Computer Assembly Plants]]
- **extension_building_types**: [[tr/Здания/Software Industry|Software Industry]], [[tr/Здания/Chip Foundries|Chip Foundries]]
- **possible_prestige_goods**: `prestige_good_apple_iphones`, `prestige_good_apple_mac`
- **potential**: скрипт, строки 39–41
- **attainable**: скрипт, строки 42–49
- **possible**: скрипт, строки 50–60
- **prosperity_modifier**:
  - `state_pop_support_movement_liberal_mult` = `0.05`
  - `building_processors_foundry_throughput_add` = `0.1` → [[tr/Здания/Chip Foundries|Chip Foundries]]
  - `country_prestige_mult` = `0.05`
- **ai_will_do**: скрипт, строки 66–72
- **ai_construction_targets**: скрипт, строки 73–80
- **ai_weight**: скрипт, строки 81–83

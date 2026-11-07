---
type: concept
description: "Вид компании «Atari» — T&R 1.13, `company_atari`"
project: vic3
source: tr
aliases: ["Atari", "company_atari"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_atari
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_digital_media_industry.txt]
---
# Atari

Вид компании · `company_atari` · `common/company_types/ztr_digital_media_industry.txt:77`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/american_atari.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_CALIFORNIA`, `STATE_NEW_YORK`
- **building_types**: [[tr/Здания/Interactive Media Industry|Interactive Media Industry]]
- **extension_building_types**: [[tr/Здания/Computer Assembly Plants|Computer Assembly Plants]]
- **possible_prestige_goods**: `prestige_good_atari_consoles`
- **potential**: скрипт, строки 94–96
- **attainable**: скрипт, строки 97–104
- **possible**: скрипт, строки 105–116
- **prosperity_modifier**:
  - `building_processors_foundry_throughput_add` = `0.05` → [[tr/Здания/Chip Foundries|Chip Foundries]]
  - `building_telecommunications_industry_throughput_add` = `0.05` → [[tr/Здания/Telecommunications Plants|Telecommunications Plants]]
- **ai_will_do**: скрипт, строки 121–127
- **ai_construction_targets**: скрипт, строки 128–135
- **ai_weight**: скрипт, строки 136–138

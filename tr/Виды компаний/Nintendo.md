---
type: concept
description: "Вид компании «Nintendo» — T&R 1.13, `company_nintendo`"
project: vic3
source: tr
aliases: ["Nintendo", "company_nintendo"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_nintendo
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_digital_media_industry.txt]
---
# Nintendo

Вид компании · `company_nintendo` · `common/company_types/ztr_digital_media_industry.txt:13`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_nintendo.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KYOTO`
- **building_types**: [[tr/Здания/Бумажные фабрики|Бумажные фабрики]], [[tr/Здания/Interactive Media Industry|Interactive Media Industry]]
- **extension_building_types**: [[tr/Здания/Entertainment Areas|Entertainment Areas]]
- **possible_prestige_goods**: `prestige_good_nintendo_consoles`
- **potential**: скрипт, строки 30–32
- **attainable**: скрипт, строки 33–40
- **possible**: скрипт, строки 41–51
- **prosperity_modifier**:
  - `goods_output_televisions_mult` = `0.1` → [[tr/Товары/Televisions|Televisions]]
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 56–62
- **ai_construction_targets**: скрипт, строки 63–70
- **ai_weight**: скрипт, строки 71–73

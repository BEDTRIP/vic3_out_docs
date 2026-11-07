---
type: concept
description: "Вид компании «Tokyo Tsushin Kogyo (Sony)» — T&R 1.13, `company_tokyo_tsushin_kogyo_sony`"
project: vic3
audience: agent
source: tr
aliases: ["Tokyo Tsushin Kogyo (Sony)", "company_tokyo_tsushin_kogyo_sony"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_tokyo_tsushin_kogyo_sony
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_tech_companies.txt]
---
# Tokyo Tsushin Kogyo (Sony)

Вид компании · `company_tokyo_tsushin_kogyo_sony` · `common/company_types/ztr_tech_companies.txt:681`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/sony.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_tech.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]], [[tr/Здания/Interactive Media Industry|Interactive Media Industry]], [[tr/Здания/Consumer Electronics Industries|Consumer Electronics Industries]]
- **extension_building_types**: [[tr/Здания/Instrument Workshops|Instrument Workshops]]
- **possible_prestige_goods**: `prestige_good_generic_records_and_films`, `prestige_good_sony_consoles`
- **potential**: скрипт, строки 700–702
- **attainable**: скрипт, строки 703–709
- **possible**: скрипт, строки 710–724
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.1`
  - `goods_output_elgar_music_mult` = `0.05` → [[tr/Товары/Entertainment|Entertainment]]
  - `building_electronics_industry_throughput_add` = `0.1` → [[tr/Здания/Electronic Components Industries|Electronic Components Industries]]
- **ai_will_do**: скрипт, строки 730–742
- **ai_construction_targets**: скрипт, строки 743–750
- **ai_weight**: скрипт, строки 751–753

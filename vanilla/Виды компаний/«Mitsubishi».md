---
type: concept
description: "Вид компании ««Mitsubishi»» — ваниль 1.13, `company_mitsubishi`"
project: vic3
audience: agent
source: vanilla
aliases: ["«Mitsubishi»", "Mitsubishi", "company_mitsubishi"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_mitsubishi
paths: [.vanillaVIC3/common/company_types/00_companies_japan.txt]
---
# «Mitsubishi»

Вид компании · `company_mitsubishi` · `common/company_types/00_companies_japan.txt:85`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_mitsubishi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[vanilla/Здания/верфи|верфи]], [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Бумажные фабрики|Бумажные фабрики]]
- **extension_building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]], [[vanilla/Здания/Моторные заводы|Моторные заводы]], [[vanilla/Здания/Артиллерийские заводы|Артиллерийские заводы]]
- **possible_prestige_goods**: `prestige_good_washi_paper`
- **potential**: скрипт, строки 110–112
- **possible**: скрипт, строки 114–128
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-industrialists-pol-str-mult|interest_group_ig_industrialists_pol_str_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-automotive-industry-throughput-add|building_automotive_industry_throughput_add]] = `0.1` → [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **ai_will_do**: скрипт, строки 135–145
- **ai_construction_targets**: скрипт, строки 147–154
- **ai_weight**: скрипт, строки 156–158

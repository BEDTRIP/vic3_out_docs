---
type: concept
description: "Вид компании ««Philips»» — TGR 1.15, `company_philips`"
project: vic3
audience: agent
source: tgr
aliases: ["«Philips»", "Philips", "company_philips"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_philips
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/«Philips»]]"
---
# «Philips»

Вид компании · `company_philips` · `common/company_types/TGR_TRADE_companies.txt:1077`

## Отличия от ваниль

- **icon**: `"gfx/interface/icons/company_icons/historical_company_icons/philips.dds"` → `"gfx/interface/icons/company_icons/historical_company_icons/maatschappij.dds"`
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **potential**: изменено
- **possible**: изменено
- **ai_will_do**: изменено
- **ai_construction_targets**: изменено
- **ai_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/maatschappij.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_HOLLAND`, `STATE_GELRE`
- **building_types**: [[tgr/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Банановые плантации|Банановые плантации]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_gros_michel_banana`
- **potential**: скрипт, строки 1099–1101
- **attainable**: скрипт, строки 1103–1112
- **possible**: скрипт, строки 1114–1122
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-max-add|country_weekly_innovation_max_add]] = `15`
- **ai_will_do**: скрипт, строки 1129–1137
- **ai_construction_targets**: скрипт, строки 1139–1150
- **ai_weight**: скрипт, строки 1152–1154

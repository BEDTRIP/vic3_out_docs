---
type: concept
description: "Вид компании ««Philips»» — TGR 1.13, `company_philips`"
project: vic3
audience: agent
source: tgr
aliases: ["«Philips»", "Konglomerat der Niederlande", "company_philips"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_philips
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/«Philips»]]"
---
# «Philips»

Вид компании · `company_philips` · `common/company_types/TGR_TRADE_companies.txt:1023`

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
- **potential**: скрипт, строки 1045–1047
- **attainable**: скрипт, строки 1049–1058
- **possible**: скрипт, строки 1060–1068
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-mult|country_weekly_innovation_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы C#^m-country-weekly-innovation-max-add|country_weekly_innovation_max_add]] = `15`
- **ai_will_do**: скрипт, строки 1075–1083
- **ai_construction_targets**: скрипт, строки 1085–1096
- **ai_weight**: скрипт, строки 1098–1100

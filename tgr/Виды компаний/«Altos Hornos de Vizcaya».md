---
type: concept
description: "Вид компании ««Altos Hornos de Vizcaya»» — TGR 1.13, `company_altos_hornos_de_vizcaya`"
project: vic3
source: tgr
aliases: ["«Altos Hornos de Vizcaya»", "Compañía de Andaluza", "company_altos_hornos_de_vizcaya"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_altos_hornos_de_vizcaya
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/«Altos Hornos de Vizcaya»]]"
---
# «Altos Hornos de Vizcaya»

Вид компании · `company_altos_hornos_de_vizcaya` · `common/company_types/TGR_TRADE_companies.txt:528`

## Отличия от ваниль

- **icon**: `"gfx/interface/icons/company_icons/historical_company_icons/basque_altos_hornos…` → `"gfx/interface/icons/company_icons/historical_company_icons/company_pedro_domec…`
- **background**: `"gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_…` → `"gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds"`
- **preferred_headquarters**: изменено
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: изменено
- **potential**: изменено
- **attainable**: изменено
- **possible**: изменено
- **ai_will_do**: изменено
- **ai_construction_targets**: изменено
- **ai_weight**: изменено
- **prestige_goods_trigger**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_pedro_domecq.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NEW_CASTILE`
- **building_types**: [[tgr/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Банановые плантации|Банановые плантации]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_generic_tools`, `prestige_good_gros_michel_banana`
- **potential**: скрипт, строки 551–553
- **attainable**: скрипт, строки 555–561
- **possible**: скрипт, строки 563–572
- **prosperity_modifier**:
  - `state_infrastructure_mult` = `0.1`
- **ai_will_do**: скрипт, строки 578–583
- **ai_construction_targets**: скрипт, строки 585–592
- **ai_weight**: скрипт, строки 594–596

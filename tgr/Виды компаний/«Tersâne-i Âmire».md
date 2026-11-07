---
type: concept
description: "Вид компании ««Tersâne-i Âmire»» — TGR 1.13, `company_imperial_arsenal`"
project: vic3
source: tgr
aliases: ["«Tersâne-i Âmire»", "Tersâne-i Âmire", "company_imperial_arsenal"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_imperial_arsenal
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/«Tersâne-i Âmire»]]"
---
# «Tersâne-i Âmire»

Вид компании · `company_imperial_arsenal` · `common/company_types/TGR_TRADE_companies.txt:808`

## Отличия от ваниль

- **icon**: `"gfx/interface/icons/company_icons/historical_company_icons/imperial_arsenal.dd…` → `"gfx/interface/icons/company_icons/historical_company_icons/ottoman_tobacco_reg…`
- **background**: `"gfx/interface/icons/company_icons/company_backgrounds/comp_illu_harbor_shipbui…` → `"gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds"`
- **building_types**: изменено
- **extension_building_types**: изменено
- **possible_prestige_goods**: добавлено
- **potential**: изменено
- **possible**: изменено
- **prosperity_modifier**: изменено
- **ai_will_do**: изменено
- **ai_construction_targets**: изменено
- **ai_weight**: изменено
- **category**: убрано

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ottoman_tobacco_regie.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_plantation.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_EASTERN_THRACE`
- **building_types**: [[tgr/Здания/Стеклозаводы|Стеклозаводы]], [[vanilla/Здания/Плантации шёлка|Плантации шёлка]], [[vanilla/Здания/Табачные плантации|Табачные плантации]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_turkish_tobacco`
- **potential**: скрипт, строки 831–833
- **attainable**: скрипт, строки 835–841
- **possible**: скрипт, строки 843–851
- **prosperity_modifier**:
  - `unit_navy_defense_mult` = `0.10`
- **ai_will_do**: скрипт, строки 857–862
- **ai_construction_targets**: скрипт, строки 864–871
- **ai_weight**: скрипт, строки 873–875

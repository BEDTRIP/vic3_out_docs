---
type: concept
description: "Вид компании «Mantero Seta» — TGR 1.13, `company_mantero_seta`"
project: vic3
source: tgr
aliases: ["Mantero Seta", "Confindustria Italiana", "company_mantero_seta"]
tags: [TGR, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_mantero_seta
paths: [TheGreatRevision/common/company_types/TGR_TRADE_companies.txt]
replaces: "[[vanilla/Виды компаний/Mantero Seta]]"
---
# Mantero Seta

Вид компании · `company_mantero_seta` · `common/company_types/TGR_TRADE_companies.txt:668`

## Отличия от ваниль

- **icon**: `"gfx/interface/icons/company_icons/historical_company_icons/company_mantero_set…` → `"gfx/interface/icons/company_icons/historical_company_icons/ilva.dds"`
- **background**: `"gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds"` → `"gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_…`
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

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/ilva.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_heavy.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_PIEDMONT`
- **building_types**: [[vanilla/Здания/Виноградники|Виноградники]], [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]], [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Серные рудники|Серные рудники]], [[vanilla/Здания/Железные дороги|Железные дороги]]
- **extension_building_types**: пусто
- **possible_prestige_goods**: `prestige_good_champagne`
- **potential**: пусто
- **attainable**: пусто
- **possible**: скрипт, строки 699–710
- **prosperity_modifier**:
  - `country_prestige_mult` = `0.05`
  - `building_synthetics_plant_throughput_add` = `0.1` → [[tgr/Здания/Заводы синтетики|Заводы синтетики]]
- **ai_will_do**: скрипт, строки 717–722
- **ai_construction_targets**: скрипт, строки 724–731
- **ai_weight**: скрипт, строки 733–735

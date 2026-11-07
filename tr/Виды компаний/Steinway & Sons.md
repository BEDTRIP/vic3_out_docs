---
type: concept
description: "Вид компании «Steinway & Sons» — T&R 1.13, `elgar_company_steinway`"
project: vic3
audience: agent
source: tr
aliases: ["Steinway & Sons", "elgar_company_steinway"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_steinway
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_entertainment_companies.txt]
---
# Steinway & Sons

Вид компании · `elgar_company_steinway` · `common/company_types/ztr_entertainment_companies.txt:9`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/elgar_instruments_steinway.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NEW_YORK`, `STATE_ELBE`
- **building_types**: [[tr/Здания/Instrument Workshops|Instrument Workshops]]
- **extension_building_types**: [[tr/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **prestige_goods_trigger**: скрипт, строки 28–33
- **potential**: скрипт, строки 34–39
- **attainable**: скрипт, строки 40–50
- **possible**: скрипт, строки 51–63
- **prosperity_modifier**:
  - `goods_output_elgar_instruments_mult` = `0.1` → [[tr/Товары/Instruments|Instruments]]
  - [[vanilla/движок/Модификаторы S#^m-state-upper-strata-standard-of-living-add|state_upper_strata_standard_of_living_add]] = `0.5`
- **ai_will_do**: скрипт, строки 68–76
- **ai_construction_targets**: скрипт, строки 77–87
- **ai_weight**: скрипт, строки 88–90

---
type: concept
description: "Вид компании «Guitarras Ramírez» — Morgenröte 1.15, `elgar_company_guitarras_ramirez`"
project: vic3
audience: agent
source: morgenrote
aliases: ["Guitarras Ramírez", "elgar_company_guitarras_ramirez"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_guitarras_ramirez
paths: [Morgenrote/common/company_types/mr_elgar_company_types.txt]
---
# Guitarras Ramírez

Вид компании · `elgar_company_guitarras_ramirez` · `common/company_types/mr_elgar_company_types.txt:382`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_guitarras_ramirez.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NEW_CASTILE`
- **building_types**: [[morgenrote/Здания/Мастерские музыкальных инструментов|Мастерские музыкальных инструментов]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **potential**: скрипт, строки 404–406
- **possible**: скрипт, строки 408–417
- **prosperity_modifier**:
  - `goods_output_elgar_instruments_mult` = `0.1` → [[morgenrote/Товары/Муз.нструменты|Муз.нструменты]]
  - [[vanilla/движок/Модификаторы S#^m-state-middle-strata-standard-of-living-add|state_middle_strata_standard_of_living_add]] = `0.5`
- **ai_will_do**: скрипт, строки 424–429
- **ai_construction_targets**: скрипт, строки 431–438
- **ai_weight**: скрипт, строки 440–442

---
type: concept
description: "Вид компании «C. Bechstein» — Morgenröte 1.13, `elgar_company_c_bechstein`"
project: vic3
audience: agent
source: morgenrote
aliases: ["C. Bechstein", "elgar_company_c_bechstein"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_c_bechstein
paths: [Morgenrote/common/company_types/mr_elgar_company_types.txt]
---
# C. Bechstein

Вид компании · `elgar_company_c_bechstein` · `common/company_types/mr_elgar_company_types.txt:254`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_c_bechstein.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BRANDENBURG`
- **building_types**: [[morgenrote/Здания/Мастерские музыкальных инструментов|Мастерские музыкальных инструментов]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **potential**: скрипт, строки 276–278
- **possible**: скрипт, строки 280–289
- **prosperity_modifier**:
  - `goods_output_elgar_music_mult` = `0.1` → [[morgenrote/Товары/Музыка|Музыка]]
  - [[vanilla/движок/Модификаторы S#^m-state-upper-strata-standard-of-living-add|state_upper_strata_standard_of_living_add]] = `0.5`
- **ai_will_do**: скрипт, строки 296–301
- **ai_construction_targets**: скрипт, строки 303–310
- **ai_weight**: скрипт, строки 312–314

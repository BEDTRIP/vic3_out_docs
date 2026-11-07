---
type: concept
description: "Вид компании «Steinway & Sons» — Morgenröte 1.13, `elgar_company_steinway`"
project: vic3
source: morgenrote
aliases: ["Steinway & Sons", "elgar_company_steinway"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_steinway
paths: [Morgenrote/common/company_types/mr_elgar_company_types.txt]
---
# Steinway & Sons

Вид компании · `elgar_company_steinway` · `common/company_types/mr_elgar_company_types.txt:60`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_steinway.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_NEW_YORK`
- **building_types**: [[morgenrote/Здания/Мастерские музыкальных инструментов|Мастерские музыкальных инструментов]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_steinway`
- **potential**: скрипт, строки 82–84
- **possible**: скрипт, строки 86–95
- **prosperity_modifier**:
  - `goods_output_elgar_instruments_mult` = `0.1` → [[morgenrote/Товары/Муз.нструменты|Муз.нструменты]]
  - `state_upper_strata_standard_of_living_add` = `0.5`
- **ai_will_do**: скрипт, строки 102–107
- **ai_construction_targets**: скрипт, строки 109–116
- **ai_weight**: скрипт, строки 118–120

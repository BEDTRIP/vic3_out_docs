---
type: concept
description: "Вид компании «Becker» — Morgenröte 1.13, `elgar_company_becker`"
project: vic3
source: morgenrote
aliases: ["Becker", "elgar_company_becker"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_becker
paths: [Morgenrote/common/company_types/mr_elgar_company_types.txt]
---
# Becker

Вид компании · `elgar_company_becker` · `common/company_types/mr_elgar_company_types.txt:124`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_becker.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_INGRIA`
- **building_types**: [[morgenrote/Здания/Мастерские музыкальных инструментов|Мастерские музыкальных инструментов]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **potential**: скрипт, строки 146–148
- **possible**: скрипт, строки 150–159
- **prosperity_modifier**:
  - `goods_output_elgar_instruments_mult` = `0.05` → [[morgenrote/Товары/Муз.нструменты|Муз.нструменты]]
  - `goods_output_elgar_music_mult` = `0.05` → [[morgenrote/Товары/Музыка|Музыка]]
  - [[vanilla/движок/Модификаторы C#^m-country-prestige-mult|country_prestige_mult]] = `0.05`
- **ai_will_do**: скрипт, строки 167–172
- **ai_construction_targets**: скрипт, строки 174–181
- **ai_weight**: скрипт, строки 183–185

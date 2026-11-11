---
type: concept
description: "Вид компании «Petrof» — Morgenröte 1.15, `elgar_company_petrof`"
project: vic3
audience: agent
source: morgenrote
aliases: ["Petrof", "elgar_company_petrof"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_petrof
paths: [Morgenrote/common/company_types/mr_elgar_company_types.txt]
---
# Petrof

Вид компании · `elgar_company_petrof` · `common/company_types/mr_elgar_company_types.txt:576`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_petrof.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BOHEMIA`
- **building_types**: [[morgenrote/Здания/Мастерские музыкальных инструментов|Мастерские музыкальных инструментов]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **potential**: скрипт, строки 598–600
- **possible**: скрипт, строки 602–611
- **prosperity_modifier**:
  - `goods_output_elgar_instruments_mult` = `0.1` → [[morgenrote/Товары/Муз.нструменты|Муз.нструменты]]
  - `goods_output_elgar_music_mult` = `0.05` → [[morgenrote/Товары/Музыка|Музыка]]
- **ai_will_do**: скрипт, строки 618–623
- **ai_construction_targets**: скрипт, строки 625–632
- **ai_weight**: скрипт, строки 634–636

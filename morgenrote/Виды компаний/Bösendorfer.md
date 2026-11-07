---
type: concept
description: "Вид компании «Bösendorfer» — Morgenröte 1.13, `elgar_company_boesendorfer`"
project: vic3
source: morgenrote
aliases: ["Bösendorfer", "elgar_company_boesendorfer"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_boesendorfer
paths: [Morgenrote/common/company_types/mr_elgar_company_types.txt]
---
# Bösendorfer

Вид компании · `elgar_company_boesendorfer` · `common/company_types/mr_elgar_company_types.txt:189`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_boesendorfer.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_AUSTRIA`
- **building_types**: [[morgenrote/Здания/Мастерские музыкальных инструментов|Мастерские музыкальных инструментов]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **potential**: скрипт, строки 211–213
- **possible**: скрипт, строки 215–224
- **prosperity_modifier**:
  - `goods_output_elgar_instruments_mult` = `0.05` → [[morgenrote/Товары/Муз.нструменты|Муз.нструменты]]
  - `goods_output_elgar_music_mult` = `0.05` → [[morgenrote/Товары/Музыка|Музыка]]
  - `state_radicals_from_political_movements_mult` = `-0.05`
- **ai_will_do**: скрипт, строки 232–237
- **ai_construction_targets**: скрипт, строки 239–246
- **ai_weight**: скрипт, строки 248–250

---
type: concept
description: "Вид компании «Maino e Orsi» — Morgenröte 1.13, `elgar_company_maino_e_orsi`"
project: vic3
source: morgenrote
aliases: ["Maino e Orsi", "elgar_company_maino_e_orsi"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_maino_e_orsi
paths: [Morgenrote/common/company_types/mr_elgar_company_types.txt]
---
# Maino e Orsi

Вид компании · `elgar_company_maino_e_orsi` · `common/company_types/mr_elgar_company_types.txt:446`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_maino_e_orsi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_LOMBARDY`
- **building_types**: [[morgenrote/Здания/Мастерские музыкальных инструментов|Мастерские музыкальных инструментов]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **potential**: скрипт, строки 468–470
- **possible**: скрипт, строки 472–481
- **prosperity_modifier**:
  - `goods_output_elgar_instruments_mult` = `0.05` → [[morgenrote/Товары/Муз.нструменты|Муз.нструменты]]
  - `goods_output_elgar_music_mult` = `0.05` → [[morgenrote/Товары/Музыка|Музыка]]
  - `country_weekly_innovation_mult` = `0.05`
- **ai_will_do**: скрипт, строки 489–494
- **ai_construction_targets**: скрипт, строки 496–503
- **ai_weight**: скрипт, строки 505–507

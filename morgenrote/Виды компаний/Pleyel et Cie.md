---
type: concept
description: "Вид компании «Pleyel et Cie» — Morgenröte 1.13, `elgar_company_pleyel`"
project: vic3
source: morgenrote
aliases: ["Pleyel et Cie", "elgar_company_pleyel"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_pleyel
paths: [Morgenrote/common/company_types/mr_elgar_company_types.txt]
---
# Pleyel et Cie

Вид компании · `elgar_company_pleyel` · `common/company_types/mr_elgar_company_types.txt:640`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_pleyel.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_ILE_DE_FRANCE`
- **building_types**: [[morgenrote/Здания/Мастерские музыкальных инструментов|Мастерские музыкальных инструментов]]
- **extension_building_types**: [[morgenrote/Здания/Издательские предприятия|Издательские предприятия]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **potential**: скрипт, строки 662–664
- **possible**: скрипт, строки 666–675
- **prosperity_modifier**:
  - `goods_output_elgar_instruments_mult` = `0.1` → [[morgenrote/Товары/Муз.нструменты|Муз.нструменты]]
  - `building_art_academy_throughput_add` = `0.05` → [[morgenrote/Здания/Академии искусств|Академии искусств]]
- **ai_will_do**: скрипт, строки 682–687
- **ai_construction_targets**: скрипт, строки 689–696
- **ai_weight**: скрипт, строки 698–700

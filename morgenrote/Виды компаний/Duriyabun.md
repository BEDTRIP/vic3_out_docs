---
type: concept
description: "Вид компании «Duriyabun» — Morgenröte 1.15, `elgar_company_duriyabun`"
project: vic3
audience: agent
source: morgenrote
aliases: ["Duriyabun", "elgar_company_duriyabun"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_duriyabun
paths: [Morgenrote/common/company_types/mr_elgar_company_types.txt]
---
# Duriyabun

Вид компании · `elgar_company_duriyabun` · `common/company_types/mr_elgar_company_types.txt:318`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_duriyabun.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BANGKOK`
- **building_types**: [[morgenrote/Здания/Мастерские музыкальных инструментов|Мастерские музыкальных инструментов]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Лесозаготовки|Лесозаготовки]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **potential**: скрипт, строки 340–342
- **possible**: скрипт, строки 344–353
- **prosperity_modifier**:
  - `goods_output_elgar_music_mult` = `0.05` → [[morgenrote/Товары/Музыка|Музыка]]
  - [[vanilla/движок/Модификаторы S#^m-state-assimilation-mult|state_assimilation_mult]] = `0.1`
- **ai_will_do**: скрипт, строки 360–365
- **ai_construction_targets**: скрипт, строки 367–374
- **ai_weight**: скрипт, строки 376–378

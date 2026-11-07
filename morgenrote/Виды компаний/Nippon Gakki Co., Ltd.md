---
type: concept
description: "Вид компании «Nippon Gakki Co., Ltd» — Morgenröte 1.13, `elgar_company_nippon_gakki`"
project: vic3
audience: agent
source: morgenrote
aliases: ["Nippon Gakki Co., Ltd", "elgar_company_nippon_gakki"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: elgar_company_nippon_gakki
paths: [Morgenrote/common/company_types/mr_elgar_company_types.txt]
---
# Nippon Gakki Co., Ltd

Вид компании · `elgar_company_nippon_gakki` · `common/company_types/mr_elgar_company_types.txt:511`

## Поля

- **icon**: `gfx/interface/icons/company_icons/elgar_instruments_nippon_gakki.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_TOKAI`
- **building_types**: [[morgenrote/Здания/Мастерские музыкальных инструментов|Мастерские музыкальных инструментов]]
- **extension_building_types**: [[vanilla/Здания/Производства инструментов|Производства инструментов]], [[vanilla/Здания/Автомобильные заводы|Автомобильные заводы]]
- **possible_prestige_goods**: `prestige_good_generic_instruments`
- **potential**: скрипт, строки 533–536
- **possible**: скрипт, строки 538–547
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-education-access-wealth-add|state_education_access_wealth_add]] = `0.005`
  - `goods_output_elgar_instruments_mult` = `0.1` → [[morgenrote/Товары/Муз.нструменты|Муз.нструменты]]
- **ai_will_do**: скрипт, строки 554–559
- **ai_construction_targets**: скрипт, строки 561–568
- **ai_weight**: скрипт, строки 570–572

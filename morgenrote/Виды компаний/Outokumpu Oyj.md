---
type: concept
description: "Вид компании «Outokumpu Oyj» — Morgenröte 1.15, `mr_company_outokumpu`"
project: vic3
audience: agent
source: morgenrote
aliases: ["Outokumpu Oyj", "mr_company_outokumpu"]
tags: [Morgenröte, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: mr_company_outokumpu
paths: [Morgenrote/common/company_types/mr_company_types.txt]
---
# Outokumpu Oyj

Вид компании · `mr_company_outokumpu` · `common/company_types/mr_company_types.txt:213`

## Поля

- **icon**: `gfx/interface/icons/company_icons/mr_outokumpu.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KUOPIO`
- **building_types**: [[vanilla/Здания/Медные рудники|Медные рудники]], [[vanilla/Здания/Железные рудники|Железные рудники]], [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **extension_building_types**: [[vanilla/Здания/Угольные шахты|Угольные шахты]], [[vanilla/Здания/Свинцовые рудники|Свинцовые рудники]]
- **possible_prestige_goods**: `prestige_good_generic_steel`
- **prestige_goods_trigger**: скрипт, строки 236–241
- **potential**: скрипт, строки 243–247
- **possible**: скрипт, строки 249–259
- **prosperity_modifier**:
  - `building_copper_mine_throughput_add` = `0.15` → [[vanilla/Здания/Медные рудники|Медные рудники]]
  - [[vanilla/движок/Модификаторы B#^m-building-iron-mine-throughput-add|building_iron_mine_throughput_add]] = `0.1` → [[vanilla/Здания/Железные рудники|Железные рудники]]
  - [[vanilla/движок/Модификаторы B#^m-building-steel-mill-throughput-add|building_steel_mill_throughput_add]] = `0.1` → [[vanilla/Здания/Сталелитейные заводы|Сталелитейные заводы]]
- **ai_will_do**: скрипт, строки 267–277
- **ai_construction_targets**: скрипт, строки 279–286
- **ai_weight**: скрипт, строки 288–290

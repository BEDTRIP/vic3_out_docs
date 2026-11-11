---
type: concept
description: "Вид компании «Siam Electricity Company Limited» — ваниль 1.15, `company_siam_electrical_company_limited`"
project: vic3
audience: agent
source: vanilla
aliases: ["Siam Electricity Company Limited", "company_siam_electrical_company_limited"]
tags: [ваниль, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_siam_electrical_company_limited
paths: [.vanillaVIC3/common/company_types/00_companies_ep2.txt]
---
# Siam Electricity Company Limited

Вид компании · `company_siam_electrical_company_limited` · `common/company_types/00_companies_ep2.txt:712`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/company_siam_electrical_company_limited.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_manufacturing_light.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_BANGKOK`
- **building_types**: [[vanilla/Здания/Электростанции|Электростанции]]
- **extension_building_types**: [[vanilla/Здания/Железные дороги|Железные дороги]]
- **possible_prestige_goods**: пусто
- **prestige_goods_trigger**: пусто
- **potential**: скрипт, строки 734–737
- **attainable**: скрипт, строки 739–747
- **possible**: скрипт, строки 749–759
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-rice-farm-throughput-add|building_rice_farm_throughput_add]] = `0.1` → [[vanilla/Здания/Рисовые поля|Рисовые поля]]
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-approval-add|interest_group_ig_landowners_approval_add]] = `3`
- **ai_will_do**: скрипт, строки 766–770
- **ai_construction_targets**: скрипт, строки 772–779
- **ai_weight**: скрипт, строки 781–783

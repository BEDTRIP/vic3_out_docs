---
type: concept
description: "Вид компании «Union Minière du Haut-Katanga» — T&R 1.13, `company_union_miniere_du_haut_katanga`"
project: vic3
audience: agent
source: tr
aliases: ["Union Minière du Haut-Katanga", "company_union_miniere_du_haut_katanga"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_union_miniere_du_haut_katanga
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_mining_companies.txt]
---
# Union Minière du Haut-Katanga

Вид компании · `company_union_miniere_du_haut_katanga` · `common/company_types/ztr_mining_companies.txt:102`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/union_miniere_du_haut_katanga.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_mining.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_FLANDERS`
- **building_types**: [[tr/Здания/Uranium Mines|Uranium Mines]], [[tr/Здания/Медные рудники|Медные рудники]]
- **extension_building_types**: [[tr/Здания/Rare Earths Mines|Rare Earths Mines]], [[tr/Здания/Advanced Ores Mines|Advanced Ores Mines]]
- **potential**: скрипт, строки 117–122
- **attainable**: скрипт, строки 123–130
- **possible**: скрипт, строки 132–146
- **prosperity_modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-power-plant-throughput-add|building_power_plant_throughput_add]] = `0.05` → [[tr/Здания/Электростанции|Электростанции]]
  - `goods_input_good_uranium_mult` = `-0.1` → [[tr/Товары/Uranium|Uranium]]
- **ai_will_do**: скрипт, строки 151–158
- **ai_construction_targets**: скрипт, строки 159–178
- **ai_weight**: скрипт, строки 179–181

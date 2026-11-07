---
type: concept
description: "Закон «Land Stewardship» — Hail Columbia 1.13, `law_usfp_tribal_land_ownership`"
project: vic3
source: hail_columbia
aliases: ["Land Stewardship", "law_usfp_tribal_land_ownership"]
tags: [hail_columbia, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_usfp_tribal_land_ownership
paths: [for addon/Hail Columbia/common/laws/usfp_native_laws.txt]
---
# Land Stewardship

Закон · `law_usfp_tribal_land_ownership` · `common/laws/usfp_native_laws.txt:52`

## Поля

- **group**: [[vanilla/Группы законов/Земельная реформа|Земельная реформа]]
- **parent**: [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]]
- **icon**: `gfx/interface/icons/law_icons/usfp_law_tribal_land_ownership.dds`
- **progressiveness**: `25`
- **modifier**:
  - `building_group_bg_agriculture_allowed_collectivization_add` = `1.0`
  - `building_group_bg_ranching_allowed_collectivization_add` = `1.0`
  - `building_group_bg_plantations_allowed_collectivization_add` = `1.0`
  - `building_subsistence_output_mult` = `0.10`
  - `building_group_bg_plantations_construction_efficiency_add` = `-0.50`
  - `building_group_bg_ranching_construction_efficiency_add` = `-0.25`
  - `building_group_bg_agriculture_construction_efficiency_add` = `-0.25`
  - `building_group_bg_extraction_allowed_collectivization_add` = `1.0`
  - `building_group_bg_extraction_throughput_add` = `-0.30`
- **is_visible**: скрипт, строки 92–97
- **unlocking_laws**: [[vanilla/Законы/Вождество|Вождество]]
- **ai_will_do**: скрипт, строки 103–105
- **ai_enact_weight_modifier**: скрипт, строки 107–114

## Ссылаются

- **Методы производства** (открывает закон): [[hail_columbia/Методы производства/Subsistence Hunting|Subsistence Hunting]]

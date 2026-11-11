---
type: concept
description: "Закон «Heavenly Land System» — Mandate of Heaven 1.15, `law_heavenly_land_system`"
project: vic3
audience: agent
source: mandate_of_heaven
aliases: ["Heavenly Land System", "law_heavenly_land_system"]
tags: [mandate_of_heaven, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_heavenly_land_system
paths: [for addon/Mandate of Heaven/common/laws/moh_flavoured_laws.txt]
---
# Heavenly Land System

Закон · `law_heavenly_land_system` · `common/laws/moh_flavoured_laws.txt:93`

## Поля

- **group**: [[vanilla/Группы законов/Земельная реформа|Земельная реформа]]
- **parent**: [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]]
- **icon**: `gfx/interface/icons/law_icons/law_heavenly_land_system.dds`
- **progressiveness**: `50`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-farmers-pol-str-mult|country_farmers_pol_str_mult]] = `0.15`
  - [[vanilla/движок/Модификаторы C#^m-country-clergymen-pol-str-mult|country_clergymen_pol_str_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-lower-strata-standard-of-living-add|state_lower_strata_standard_of_living_add]] = `0.1`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-allowed-collectivization-add|building_group_bg_agriculture_allowed_collectivization_add]] = `0.5`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-ranching-allowed-collectivization-add|building_group_bg_ranching_allowed_collectivization_add]] = `0.5`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-landowners-approval-add|interest_group_ig_landowners_approval_add]] = `-5`
- **is_visible**: скрипт, строки 110–112
- **on_enact**: пусто
- **ai_enact_weight_modifier**: скрипт, строки 117–124

---
type: concept
description: "Закон «Basic Enviroment Protection» — T&R 1.13, `law_basic_protection`"
project: vic3
audience: agent
source: tr
aliases: ["Basic Enviroment Protection", "law_basic_protection"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_basic_protection
paths: [TechRes+Kuromi/t&r/common/laws/ztr_environmental_policy.txt]
---
# Basic Enviroment Protection

Закон · `law_basic_protection` · `common/laws/ztr_environmental_policy.txt:22`

## Поля

- **group**: [[tr/Группы законов/Environmental Policy|Environmental Policy]]
- **icon**: `gfx/interface/icons/law_icons/law_basic_protection.dds`
- **progressiveness**: `50`
- **unlocking_technologies**: [[tr/Технологии/Counterculture|Counterculture]]
- **modifier**:
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-mining-throughput-add|building_group_bg_mining_throughput_add]] = `-0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-extraction-throughput-add|building_group_bg_extraction_throughput_add]] = `-0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-heavy-industry-throughput-add|building_group_bg_heavy_industry_throughput_add]] = `-0.01`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-light-industry-throughput-add|building_group_bg_light_industry_throughput_add]] = `-0.01`
- **ai_enact_weight_modifier**: скрипт, строки 40–47
- **institution**: `institution_environmental_policy`
- **institution_modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.01`
- **on_activate**: скрипт, строки 55–57

## Ссылаются

- **Идеологии** (lawgroup_environmental_policy: approve): [[tr/Идеологии/Extreme Environmentalist|Extreme Environmentalist]], [[tr/Идеологии/Moderate Environmentalist|Moderate Environmentalist]], [[tr/Идеологии/Neoliberal Environmentalist|Neoliberal Environmentalist]]
- **Идеологии** (lawgroup_environmental_policy: disapprove): [[tr/Идеологии/Negligent Environmentalist|Negligent Environmentalist]]
- **Методы производства** (запрещает закон): [[tr/Методы производства/Coal-Fired Power Plant (pm_coal-fired_plant_2)|Coal-Fired Power Plant (pm_coal-fired_plant_2)]], [[tr/Методы производства/Coal-Fired Power Plant (pm_coal-fired_plant_3)|Coal-Fired Power Plant (pm_coal-fired_plant_3)]], [[tr/Методы производства/No Recycling|No Recycling]], [[tr/Методы производства/Угольная электростанция|Угольная электростанция]]

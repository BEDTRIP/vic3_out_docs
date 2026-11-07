---
type: concept
description: "Закон «Active Restoration» — T&R 1.13, `law_active_restoration`"
project: vic3
source: tr
aliases: ["Active Restoration", "law_active_restoration"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_active_restoration
paths: [TechRes+Kuromi/t&r/common/laws/ztr_environmental_policy.txt]
---
# Active Restoration

Закон · `law_active_restoration` · `common/laws/ztr_environmental_policy.txt:60`

## Поля

- **group**: [[tr/Группы законов/Environmental Policy|Environmental Policy]]
- **icon**: `gfx/interface/icons/law_icons/law_active_restoration.dds`
- **progressiveness**: `100`
- **unlocking_technologies**: [[tr/Технологии/Circular Economy|Circular Economy]]
- **modifier**:
  - `building_group_bg_mining_throughput_add` = `-0.1`
  - `building_group_bg_extraction_throughput_add` = `-0.1`
  - `building_group_bg_heavy_industry_throughput_add` = `-0.02`
  - `building_group_bg_light_industry_throughput_add` = `-0.02`
- **ai_enact_weight_modifier**: скрипт, строки 78–85
- **institution**: `institution_environmental_policy`
- **institution_modifier**:
  - `state_pollution_reduction_health_mult` = `-0.1`
  - `state_mortality_mult` = `-0.005`
  - `state_turmoil_effects_mult` = `-0.02`
  - `interest_group_ig_industrialists_pol_str_mult` = `-0.1`
- **on_activate**: скрипт, строки 95–97

## Ссылаются

- **Идеологии** (lawgroup_environmental_policy: disapprove): [[tr/Идеологии/Neoliberal Environmentalist|Neoliberal Environmentalist]]
- **Идеологии** (lawgroup_environmental_policy: neutral): [[tr/Идеологии/Moderate Environmentalist|Moderate Environmentalist]]
- **Идеологии** (lawgroup_environmental_policy: strongly_approve): [[tr/Идеологии/Extreme Environmentalist|Extreme Environmentalist]]
- **Идеологии** (lawgroup_environmental_policy: strongly_disapprove): [[tr/Идеологии/Negligent Environmentalist|Negligent Environmentalist]]
- **Методы производства** (запрещает закон): [[tr/Методы производства/Coal-Fired Power Plant (pm_coal-fired_plant_2)|Coal-Fired Power Plant (pm_coal-fired_plant_2)]], [[tr/Методы производства/Coal-Fired Power Plant (pm_coal-fired_plant_3)|Coal-Fired Power Plant (pm_coal-fired_plant_3)]], [[tr/Методы производства/No Recycling|No Recycling]], [[tr/Методы производства/Oil-Fired Power Plant (pm_oil-fired_plant_2)|Oil-Fired Power Plant (pm_oil-fired_plant_2)]], [[tr/Методы производства/Oil-Fired Power Plant (pm_oil-fired_plant_3)|Oil-Fired Power Plant (pm_oil-fired_plant_3)]], [[tr/Методы производства/Waste Incinerator|Waste Incinerator]], [[tr/Методы производства/Мазутная электростанция|Мазутная электростанция]], [[tr/Методы производства/Угольная электростанция|Угольная электростанция]]

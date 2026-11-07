---
type: concept
description: "Закон «Restrict Hazardous Mining» — T&R 1.13, `law_mining_restrict_hazardous`"
project: vic3
source: tr
aliases: ["Restrict Hazardous Mining", "law_mining_restrict_hazardous"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_mining_restrict_hazardous
paths: [TechRes+Kuromi/t&r/common/laws/ztr_mining_policy.txt]
---
# Restrict Hazardous Mining

Закон · `law_mining_restrict_hazardous` · `common/laws/ztr_mining_policy.txt:18`

## Поля

- **group**: [[tr/Группы законов/Mining Policy|Mining Policy]]
- **icon**: `gfx/interface/icons/law_icons/no_dangerous_mines.dds`
- **progressiveness**: `0`
- **unlocking_technologies**: [[tr/Технологии/Nature Protection|Nature Protection]]
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.02`
- **on_activate**: скрипт, строки 33–35
- **ai_enact_weight_modifier**: скрипт, строки 37–44

## Ссылаются

- **Идеологии** (lawgroup_mining_policy: approve): [[tr/Идеологии/Moderate Environmentalist|Moderate Environmentalist]], [[tr/Идеологии/Neoliberal Environmentalist|Neoliberal Environmentalist]]
- **Идеологии** (lawgroup_mining_policy: neutral): [[tr/Идеологии/Extreme Environmentalist|Extreme Environmentalist]], [[tr/Идеологии/Negligent Environmentalist|Negligent Environmentalist]]

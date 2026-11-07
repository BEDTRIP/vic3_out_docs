---
type: concept
description: "Закон «Polluting Mining Banned» — T&R 1.13, `law_polluting_mining_banned`"
project: vic3
source: tr
aliases: ["Polluting Mining Banned", "law_polluting_mining_banned"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_polluting_mining_banned
paths: [TechRes+Kuromi/t&r/common/laws/ztr_mining_policy.txt]
---
# Polluting Mining Banned

Закон · `law_polluting_mining_banned` · `common/laws/ztr_mining_policy.txt:84`

## Поля

- **group**: [[tr/Группы законов/Mining Policy|Mining Policy]]
- **icon**: `gfx/interface/icons/law_icons/no_poor_mines.dds`
- **progressiveness**: `150`
- **disallowing_laws**: `law_env_no_protection`
- **unlocking_technologies**: [[tr/Технологии/Environmentalism|Environmentalism]]
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.1`
- **ai_enact_weight_modifier**: скрипт, строки 103–110
- **on_activate**: скрипт, строки 112–137

## Ссылаются

- **Идеологии** (lawgroup_mining_policy: disapprove): [[tr/Идеологии/Moderate Environmentalist|Moderate Environmentalist]]
- **Идеологии** (lawgroup_mining_policy: strongly_approve): [[tr/Идеологии/Extreme Environmentalist|Extreme Environmentalist]]
- **Идеологии** (lawgroup_mining_policy: strongly_disapprove): [[tr/Идеологии/Negligent Environmentalist|Negligent Environmentalist]], [[tr/Идеологии/Neoliberal Environmentalist|Neoliberal Environmentalist]]

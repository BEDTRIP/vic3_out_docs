---
type: concept
description: "Закон «Strategic Mining» — T&R 1.13, `law_mining_strategic`"
project: vic3
source: tr
aliases: ["Strategic Mining", "law_mining_strategic"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_mining_strategic
paths: [TechRes+Kuromi/t&r/common/laws/ztr_mining_policy.txt]
---
# Strategic Mining

Закон · `law_mining_strategic` · `common/laws/ztr_mining_policy.txt:47`

## Поля

- **group**: [[tr/Группы законов/Mining Policy|Mining Policy]]
- **icon**: `gfx/interface/icons/law_icons/strategic_mines.dds`
- **progressiveness**: `100`
- **disallowing_laws**: `law_env_no_protection`
- **unlocking_technologies**: [[tr/Технологии/Social Democracy|Social Democracy]]
- **modifier**:
  - `building_advancedores_mine_throughput_add` = `0.05` → [[tr/Здания/Advanced Ores Mines|Advanced Ores Mines]]
  - `building_rare_earths_mine_throughput_add` = `0.05` → [[tr/Здания/Rare Earths Mines|Rare Earths Mines]]
  - [[vanilla/движок/Модификаторы B#^m-building-minimum-wage-mult|building_minimum_wage_mult]] = `0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.05`
- **on_activate**: скрипт, строки 69–71
- **ai_enact_weight_modifier**: скрипт, строки 74–81

## Ссылаются

- **Идеологии** (lawgroup_mining_policy: approve): [[tr/Идеологии/Extreme Environmentalist|Extreme Environmentalist]]
- **Идеологии** (lawgroup_mining_policy: disapprove): [[tr/Идеологии/Negligent Environmentalist|Negligent Environmentalist]], [[tr/Идеологии/Neoliberal Environmentalist|Neoliberal Environmentalist]]
- **Идеологии** (lawgroup_mining_policy: neutral): [[tr/Идеологии/Moderate Environmentalist|Moderate Environmentalist]]

---
type: concept
description: "Закон «Mixed System» — TGR 1.15, `law_mixed_system`"
project: vic3
audience: agent
source: tgr
aliases: ["Mixed System", "law_mixed_system"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_mixed_system
paths: [TheGreatRevision/common/laws/TGR_POLITICS_election_system.txt]
---
# Mixed System

Закон · `law_mixed_system` · `common/laws/TGR_POLITICS_election_system.txt:82`

## Поля

- **group**: [[tgr/Группы законов/Election System|Election System]]
- **icon**: `gfx/interface/icons/law_icons/universal_suffrage_2.dds`
- **progressiveness**: `50`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-size-add|country_legitimacy_govt_size_add]] = `1`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-votes-add|country_legitimacy_govt_total_votes_add]] = `100`
  - [[vanilla/движок/Модификаторы C#^m-country-electoral-confidence-impact-mult|country_electoral_confidence_impact_mult]] = `-0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-ideological-incoherence-mult|country_legitimacy_ideological_incoherence_mult]] = `-0.15`
  - [[vanilla/движок/Модификаторы S#^m-state-bureaucracy-population-base-cost-factor-mult|state_bureaucracy_population_base_cost_factor_mult]] = `0.15`
- **disallowing_laws**: [[tgr/Законы/Автократия|Автократия]], [[tgr/Законы/Технократия|Технократия]], [[tgr/Законы/Олигархия|Олигархия]], [[tgr/Законы/Анархия|Анархия]]
- **unlocking_laws**: пусто
- **on_enact**: пусто
- **ai_enact_weight_modifier**: скрипт, строки 112–120

## Ссылаются

- **Идеологии** (lawgroup_election_system: approve): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Пролетарство|Пролетарство]], [[tgr/Идеологии/Традиционализм|Традиционализм]]
- **Идеологии** (lawgroup_election_system: disapprove): [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Позитивист (ideology_positivist_movement)|Позитивист (ideology_positivist_movement)]]
- **Идеологии** (lawgroup_election_system: neutral): [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[tgr/Идеологии/Радикализм (ideology_radical_movement)|Радикализм (ideology_radical_movement)]], [[tgr/Идеологии/Революционный социализм|Революционный социализм]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_election_system: strongly_approve): [[tgr/Идеологии/Роялизм|Роялизм]]

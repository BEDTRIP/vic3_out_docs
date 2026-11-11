---
type: concept
description: "Закон «Proportional System» — TGR 1.15, `law_proportional_system`"
project: vic3
audience: agent
source: tgr
aliases: ["Proportional System", "law_proportional_system"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_proportional_system
paths: [TheGreatRevision/common/laws/TGR_POLITICS_election_system.txt]
---
# Proportional System

Закон · `law_proportional_system` · `common/laws/TGR_POLITICS_election_system.txt:178`

## Поля

- **group**: [[tgr/Группы законов/Election System|Election System]]
- **icon**: `gfx/interface/icons/law_icons/universal_suffrage.dds`
- **progressiveness**: `50`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-size-add|country_legitimacy_govt_size_add]] = `2`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-votes-add|country_legitimacy_govt_total_votes_add]] = `100`
  - [[vanilla/движок/Модификаторы C#^m-country-electoral-confidence-impact-mult|country_electoral_confidence_impact_mult]] = `0.50`
  - [[vanilla/движок/Модификаторы S#^m-state-bureaucracy-population-base-cost-factor-mult|state_bureaucracy_population_base_cost_factor_mult]] = `0.25`
- **disallowing_laws**: [[tgr/Законы/Автократия|Автократия]], [[tgr/Законы/Технократия|Технократия]], [[tgr/Законы/Олигархия|Олигархия]], [[tgr/Законы/Анархия|Анархия]], [[tgr/Законы/Голосуют землевладельцы|Голосуют землевладельцы]], [[tgr/Законы/Голосуют богатые|Голосуют богатые]], [[tgr/Законы/Имущественный ценз|Имущественный ценз]]
- **unlocking_laws**: пусто
- **on_enact**: пусто
- **ai_enact_weight_modifier**: скрипт, строки 210–218

## Ссылаются

- **Идеологии** (lawgroup_election_system: disapprove): [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Революционный социализм|Революционный социализм]], [[tgr/Идеологии/Роялизм|Роялизм]], [[tgr/Идеологии/Традиционализм|Традиционализм]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_election_system: neutral): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]]
- **Идеологии** (lawgroup_election_system: strongly_approve): [[tgr/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Пролетарство|Пролетарство]], [[tgr/Идеологии/Радикализм (ideology_radical_movement)|Радикализм (ideology_radical_movement)]], [[tgr/Идеологии/Социалисты|Социалисты]]
- **Идеологии** (lawgroup_election_system: strongly_disapprove): [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Позитивист (ideology_positivist_movement)|Позитивист (ideology_positivist_movement)]]

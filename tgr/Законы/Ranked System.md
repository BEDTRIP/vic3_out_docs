---
type: concept
description: "Закон «Ranked System» — TGR 1.13, `law_ranked_system`"
project: vic3
audience: agent
source: tgr
aliases: ["Ranked System", "law_ranked_system"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_ranked_system
paths: [TheGreatRevision/common/laws/TGR_POLITICS_election_system.txt]
---
# Ranked System

Закон · `law_ranked_system` · `common/laws/TGR_POLITICS_election_system.txt:123`

## Поля

- **group**: [[tgr/Группы законов/Election System|Election System]]
- **icon**: `gfx/interface/icons/law_icons/elected_bureaucrats.dds`
- **progressiveness**: `50`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-size-add|country_legitimacy_govt_size_add]] = `1`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-votes-add|country_legitimacy_govt_total_votes_add]] = `100`
  - [[vanilla/движок/Модификаторы C#^m-country-electoral-confidence-impact-mult|country_electoral_confidence_impact_mult]] = `0.10`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-ideological-incoherence-mult|country_legitimacy_ideological_incoherence_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-bureaucracy-population-base-cost-factor-mult|state_bureaucracy_population_base_cost_factor_mult]] = `0.25`
- **on_enact**: пусто
- **disallowing_laws**: [[tgr/Законы/Автократия|Автократия]], [[tgr/Законы/Технократия|Технократия]], [[tgr/Законы/Олигархия|Олигархия]], [[tgr/Законы/Анархия|Анархия]], [[tgr/Законы/Однопартийное государство|Однопартийное государство]]
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **ai_enact_weight_modifier**: скрипт, строки 158–175

## Ссылаются

- **Идеологии** (lawgroup_election_system: approve): [[tgr/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Позитивист (ideology_positivist)|Позитивист (ideology_positivist)]], [[tgr/Идеологии/Позитивист (ideology_positivist_movement)|Позитивист (ideology_positivist_movement)]], [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Радикализм (ideology_radical)|Радикализм (ideology_radical)]], [[tgr/Идеологии/Радикализм (ideology_radical_movement)|Радикализм (ideology_radical_movement)]], [[tgr/Идеологии/Реформы|Реформы]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_election_system: disapprove): [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist_movement)|Авангардизм (ideology_vanguardist_movement)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Традиционализм|Традиционализм]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_election_system: neutral): [[tgr/Идеологии/Анархизм|Анархизм]], [[tgr/Идеологии/Роялизм|Роялизм]]
- **Идеологии** (lawgroup_election_system: strongly_approve): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]]

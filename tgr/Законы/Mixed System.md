---
type: concept
description: "Закон «Mixed System» — TGR 1.13, `law_mixed_system`"
project: vic3
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
  - `country_legitimacy_govt_size_add` = `1`
  - `country_legitimacy_govt_total_votes_add` = `100`
  - `country_electoral_confidence_impact_mult` = `-0.10`
  - `country_legitimacy_ideological_incoherence_mult` = `-0.15`
  - `state_bureaucracy_population_base_cost_factor_mult` = `0.15`
- **disallowing_laws**: [[tgr/Законы/Автократия|Автократия]], [[tgr/Законы/Технократия|Технократия]], [[tgr/Законы/Олигархия|Олигархия]], [[tgr/Законы/Анархия|Анархия]]
- **unlocking_laws**: пусто
- **on_enact**: пусто
- **ai_enact_weight_modifier**: скрипт, строки 112–120

## Ссылаются

- **Идеологии** (lawgroup_election_system: approve): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Радикализм (ideology_radical_movement)|Радикализм (ideology_radical_movement)]], [[tgr/Идеологии/Реформы|Реформы]], [[tgr/Идеологии/Традиционализм|Традиционализм]]
- **Идеологии** (lawgroup_election_system: disapprove): [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Позитивист (ideology_positivist)|Позитивист (ideology_positivist)]], [[tgr/Идеологии/Позитивист (ideology_positivist_movement)|Позитивист (ideology_positivist_movement)]]
- **Идеологии** (lawgroup_election_system: neutral): [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist_movement)|Авангардизм (ideology_vanguardist_movement)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Анархизм|Анархизм]], [[tgr/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Радикализм (ideology_radical)|Радикализм (ideology_radical)]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_election_system: strongly_approve): [[tgr/Идеологии/Роялизм|Роялизм]]

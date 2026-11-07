---
type: concept
description: "Закон «Majoritarian System» — TGR 1.13, `law_majoritarian_system`"
project: vic3
source: tgr
aliases: ["Majoritarian System", "law_majoritarian_system"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_majoritarian_system
paths: [TheGreatRevision/common/laws/TGR_POLITICS_election_system.txt]
---
# Majoritarian System

Закон · `law_majoritarian_system` · `common/laws/TGR_POLITICS_election_system.txt:42`

## Поля

- **group**: [[tgr/Группы законов/Election System|Election System]]
- **icon**: `gfx/interface/icons/law_icons/proportional_taxation.dds`
- **progressiveness**: `50`
- **disallowing_laws**: [[tgr/Законы/Автократия|Автократия]], [[tgr/Законы/Технократия|Технократия]], [[tgr/Законы/Олигархия|Олигархия]], [[tgr/Законы/Анархия|Анархия]]
- **unlocking_technologies**: пусто
- **modifier**:
  - `country_legitimacy_govt_total_votes_add` = `75`
  - `country_legitimacy_headofstate_add` = `25`
  - `country_electoral_confidence_impact_mult` = `-0.15`
  - `country_legitimacy_ideological_incoherence_mult` = `2.0`
- **on_enact**: пусто
- **ai_enact_weight_modifier**: скрипт, строки 71–79

## Ссылаются

- **Идеологии** (lawgroup_election_system: approve): [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist_movement)|Авангардизм (ideology_vanguardist_movement)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Позитивист (ideology_positivist)|Позитивист (ideology_positivist)]], [[tgr/Идеологии/Позитивист (ideology_positivist_movement)|Позитивист (ideology_positivist_movement)]], [[tgr/Идеологии/Роялизм|Роялизм]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_election_system: disapprove): [[tgr/Идеологии/Анархизм|Анархизм]], [[tgr/Идеологии/Радикализм (ideology_radical)|Радикализм (ideology_radical)]]
- **Идеологии** (lawgroup_election_system: neutral): [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Радикализм (ideology_radical_movement)|Радикализм (ideology_radical_movement)]], [[tgr/Идеологии/Реформы|Реформы]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]], [[tgr/Идеологии/Традиционализм|Традиционализм]]

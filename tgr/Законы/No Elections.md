---
type: concept
description: "Закон «No Elections» — TGR 1.13, `law_no_election`"
project: vic3
audience: agent
source: tgr
aliases: ["No Elections", "law_no_election"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_no_election
paths: [TheGreatRevision/common/laws/TGR_POLITICS_election_system.txt]
---
# No Elections

Закон · `law_no_election` · `common/laws/TGR_POLITICS_election_system.txt:1`

## Поля

- **group**: [[tgr/Группы законов/Election System|Election System]]
- **icon**: `gfx/interface/icons/law_icons/no_home_affairs.dds`
- **progressiveness**: `50`
- **disallowing_laws**: [[tgr/Законы/Всеобщее избирательное право|Всеобщее избирательное право]], [[tgr/Законы/Имущественный ценз|Имущественный ценз]], [[tgr/Законы/Однопартийное государство|Однопартийное государство]], [[tgr/Законы/Голосуют землевладельцы|Голосуют землевладельцы]], [[tgr/Законы/Голосуют богатые|Голосуют богатые]], [[tgr/Законы/Анархия|Анархия]]
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **on_enact**: пусто
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-voting-power-mult|country_voting_power_mult]] = `-0.25`
- **ai_enact_weight_modifier**: скрипт, строки 32–39

## Ссылаются

- **Идеологии** (lawgroup_election_system: approve): [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Анархизм|Анархизм]], [[tgr/Идеологии/Традиционализм|Традиционализм]]
- **Идеологии** (lawgroup_election_system: disapprove): [[tgr/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Позитивист (ideology_positivist)|Позитивист (ideology_positivist)]], [[tgr/Идеологии/Позитивист (ideology_positivist_movement)|Позитивист (ideology_positivist_movement)]], [[tgr/Идеологии/Радикализм (ideology_radical)|Радикализм (ideology_radical)]], [[tgr/Идеологии/Радикализм (ideology_radical_movement)|Радикализм (ideology_radical_movement)]], [[tgr/Идеологии/Реформы|Реформы]]
- **Идеологии** (lawgroup_election_system: neutral): [[tgr/Идеологии/Роялизм|Роялизм]]
- **Идеологии** (lawgroup_election_system: strongly_approve): [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist_movement)|Авангардизм (ideology_vanguardist_movement)]], [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_election_system: strongly_disapprove): [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]

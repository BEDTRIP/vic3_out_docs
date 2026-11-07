---
type: concept
description: "Закон «Restricted Parliamentary Authority» — TGR 1.13, `law_restricted_parliamentary_authority`"
project: vic3
source: tgr
aliases: ["Restricted Parliamentary Authority", "law_restricted_parliamentary_authority"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_restricted_parliamentary_authority
paths: [TheGreatRevision/common/laws/TGR_POLITICS_legislative process.txt]
---
# Restricted Parliamentary Authority

Закон · `law_restricted_parliamentary_authority` · `common/laws/TGR_POLITICS_legislative process.txt:44`

## Поля

- **group**: [[tgr/Группы законов/Legislative process|Legislative process]]
- **icon**: `gfx/interface/icons/law_icons/noseperation.dds`
- **progressiveness**: `50`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-votes-add|country_legitimacy_govt_total_votes_add]] = `-25`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-clout-add|country_legitimacy_govt_total_clout_add]] = `25`
  - [[vanilla/движок/Модификаторы C#^m-country-law-enactment-stall-mult|country_law_enactment_stall_mult]] = `-0.10`
  - [[vanilla/движок/Модификаторы P#^m-political-movement-radicalism-from-enactment-disapproval-mult|political_movement_radicalism_from_enactment_disapproval_mult]] = `0.20`
- **disallowing_laws**: [[tgr/Законы/Всеобщее избирательное право|Всеобщее избирательное право]], [[tgr/Законы/Анархия|Анархия]]
- **unlocking_laws**: пусто
- **on_enact**: пусто
- **ai_enact_weight_modifier**: скрипт, строки 71–79

## Ссылаются

- **Идеологии** (lawgroup_legislative_process: approve): [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist_movement)|Авангардизм (ideology_vanguardist_movement)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Позитивист (ideology_positivist)|Позитивист (ideology_positivist)]], [[tgr/Идеологии/Позитивист (ideology_positivist_movement)|Позитивист (ideology_positivist_movement)]], [[tgr/Идеологии/Роялизм|Роялизм]], [[tgr/Идеологии/Теократия|Теократия]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_legislative_process: disapprove): [[tgr/Идеологии/Анархизм|Анархизм]], [[tgr/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Нигилизм|Нигилизм]], [[tgr/Идеологии/Радикализм (ideology_radical)|Радикализм (ideology_radical)]], [[tgr/Идеологии/Радикализм (ideology_radical_movement)|Радикализм (ideology_radical_movement)]], [[tgr/Идеологии/Республиканство|Республиканство]], [[tgr/Идеологии/Реформы|Реформы]]
- **Идеологии** (lawgroup_legislative_process: neutral): [[tgr/Идеологии/Традиционализм|Традиционализм]], [[tgr/Идеологии/Умеренные взгляды|Умеренные взгляды]]
- **Идеологии** (lawgroup_legislative_process: strongly_disapprove): [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]

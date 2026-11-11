---
type: concept
description: "Закон «Unicameral Parliamentary System» — TGR 1.15, `law_unicameral_parliamentary_system`"
project: vic3
audience: agent
source: tgr
aliases: ["Unicameral Parliamentary System", "law_unicameral_parliamentary_system"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_unicameral_parliamentary_system
paths: [TheGreatRevision/common/laws/TGR_POLITICS_legislative process.txt]
---
# Unicameral Parliamentary System

Закон · `law_unicameral_parliamentary_system` · `common/laws/TGR_POLITICS_legislative process.txt:116`

## Поля

- **group**: [[tgr/Группы законов/Legislative process|Legislative process]]
- **icon**: `gfx/interface/icons/law_icons/parliamentary_republic.dds`
- **progressiveness**: `50`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-votes-add|country_legitimacy_govt_total_votes_add]] = `50`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-clout-add|country_legitimacy_govt_total_clout_add]] = `-15`
  - [[vanilla/движок/Модификаторы C#^m-country-law-enactment-speed-mult|country_law_enactment_speed_mult]] = `-0.20`
  - [[vanilla/движок/Модификаторы C#^m-country-law-enactment-success-add|country_law_enactment_success_add]] = `0.10`
- **disallowing_laws**: [[tgr/Законы/Автократия|Автократия]], [[tgr/Законы/Технократия|Технократия]], [[tgr/Законы/Олигархия|Олигархия]], [[tgr/Законы/Анархия|Анархия]]
- **unlocking_laws**: пусто
- **on_enact**: пусто
- **ai_enact_weight_modifier**: скрипт, строки 145–153

## Ссылаются

- **Идеологии** (lawgroup_legislative_process: approve): [[tgr/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Пролетарство|Пролетарство]], [[tgr/Идеологии/Радикализм (ideology_radical_movement)|Радикализм (ideology_radical_movement)]], [[tgr/Идеологии/Республиканство|Республиканство]], [[tgr/Идеологии/Социалисты|Социалисты]]
- **Идеологии** (lawgroup_legislative_process: disapprove): [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Позитивист (ideology_positivist_movement)|Позитивист (ideology_positivist_movement)]], [[tgr/Идеологии/Революционный социализм|Революционный социализм]], [[tgr/Идеологии/Роялизм|Роялизм]]
- **Идеологии** (lawgroup_legislative_process: neutral): [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Нигилизм|Нигилизм]], [[tgr/Идеологии/Теократия|Теократия]], [[tgr/Идеологии/Традиционализм|Традиционализм]], [[tgr/Идеологии/Умеренные взгляды|Умеренные взгляды]]
- **Идеологии** (lawgroup_legislative_process: strongly_approve): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]]
- **Идеологии** (lawgroup_legislative_process: strongly_disapprove): [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]

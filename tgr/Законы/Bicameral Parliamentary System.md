---
type: concept
description: "Закон «Bicameral Parliamentary System» — TGR 1.15, `law_bicameral_parliamentary_system`"
project: vic3
audience: agent
source: tgr
aliases: ["Bicameral Parliamentary System", "law_bicameral_parliamentary_system"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_bicameral_parliamentary_system
paths: [TheGreatRevision/common/laws/TGR_POLITICS_legislative process.txt]
---
# Bicameral Parliamentary System

Закон · `law_bicameral_parliamentary_system` · `common/laws/TGR_POLITICS_legislative process.txt:156`

## Поля

- **group**: [[tgr/Группы законов/Legislative process|Legislative process]]
- **icon**: `gfx/interface/icons/law_icons/separated_powers.dds`
- **progressiveness**: `50`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-votes-add|country_legitimacy_govt_total_votes_add]] = `75`
  - [[vanilla/движок/Модификаторы C#^m-country-legitimacy-govt-total-clout-add|country_legitimacy_govt_total_clout_add]] = `-25`
  - [[vanilla/движок/Модификаторы C#^m-country-law-enactment-speed-mult|country_law_enactment_speed_mult]] = `-0.40`
  - [[vanilla/движок/Модификаторы C#^m-country-law-enactment-success-add|country_law_enactment_success_add]] = `0.20`
- **on_enact**: пусто
- **disallowing_laws**: [[tgr/Законы/Автократия|Автократия]], [[tgr/Законы/Технократия|Технократия]], [[tgr/Законы/Олигархия|Олигархия]], [[tgr/Законы/Анархия|Анархия]], [[tgr/Законы/Однопартийное государство|Однопартийное государство]], [[tgr/Законы/Голосуют землевладельцы|Голосуют землевладельцы]], [[tgr/Законы/Голосуют богатые|Голосуют богатые]]
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **ai_enact_weight_modifier**: скрипт, строки 193–210

## Ссылаются

- **Идеологии** (lawgroup_legislative_process: approve): [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Пролетарство|Пролетарство]], [[tgr/Идеологии/Республиканство|Республиканство]]
- **Идеологии** (lawgroup_legislative_process: disapprove): [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Позитивист (ideology_positivist_movement)|Позитивист (ideology_positivist_movement)]], [[tgr/Идеологии/Роялизм|Роялизм]], [[tgr/Идеологии/Теократия|Теократия]], [[tgr/Идеологии/Традиционализм|Традиционализм]], [[tgr/Идеологии/Умеренные взгляды|Умеренные взгляды]]
- **Идеологии** (lawgroup_legislative_process: neutral): [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Нигилизм|Нигилизм]]
- **Идеологии** (lawgroup_legislative_process: strongly_approve): [[tgr/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[tgr/Идеологии/Радикализм (ideology_radical_movement)|Радикализм (ideology_radical_movement)]], [[tgr/Идеологии/Социалисты|Социалисты]]
- **Идеологии** (lawgroup_legislative_process: strongly_disapprove): [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Революционный социализм|Революционный социализм]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]

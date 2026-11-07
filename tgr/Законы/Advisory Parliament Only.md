---
type: concept
description: "Закон «Advisory Parliament Only» — TGR 1.13, `law_advisory_parliament_only`"
project: vic3
source: tgr
aliases: ["Advisory Parliament Only", "law_advisory_parliament_only"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_advisory_parliament_only
paths: [TheGreatRevision/common/laws/TGR_POLITICS_legislative process.txt]
---
# Advisory Parliament Only

Закон · `law_advisory_parliament_only` · `common/laws/TGR_POLITICS_legislative process.txt:1`

## Поля

- **group**: [[tgr/Группы законов/Legislative process|Legislative process]]
- **icon**: `gfx/interface/icons/law_icons/advice.dds`
- **progressiveness**: `50`
- **disallowing_laws**: [[tgr/Законы/Всеобщее избирательное право|Всеобщее избирательное право]], [[tgr/Законы/Имущественный ценз|Имущественный ценз]], [[tgr/Законы/Анархия|Анархия]]
- **unlocking_laws**: пусто
- **unlocking_technologies**: пусто
- **on_enact**: пусто
- **modifier**:
  - `country_legitimacy_govt_total_votes_add` = `-50`
  - `country_legitimacy_govt_total_clout_add` = `50`
  - `country_law_enactment_stall_mult` = `-0.20`
  - `political_movement_radicalism_from_enactment_disapproval_mult` = `0.40`
- **ai_enact_weight_modifier**: скрипт, строки 34–41

## Ссылаются

- **Идеологии** (lawgroup_legislative_process: disapprove): [[tgr/Идеологии/Джексонианский демократ|Джексонианский демократ]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Нигилизм|Нигилизм]], [[tgr/Идеологии/Республиканство|Республиканство]], [[tgr/Идеологии/Традиционализм|Традиционализм]], [[tgr/Идеологии/Умеренные взгляды|Умеренные взгляды]]
- **Идеологии** (lawgroup_legislative_process: neutral): [[tgr/Идеологии/Либерализм (ideology_liberal_leader)|Либерализм (ideology_liberal_leader)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]], [[tgr/Идеологии/Позитивист (ideology_positivist)|Позитивист (ideology_positivist)]], [[tgr/Идеологии/Позитивист (ideology_positivist_movement)|Позитивист (ideology_positivist_movement)]], [[tgr/Идеологии/Роялизм|Роялизм]], [[tgr/Идеологии/Теократия|Теократия]]
- **Идеологии** (lawgroup_legislative_process: strongly_approve): [[tgr/Идеологии/Абсолютизм|Абсолютизм]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist)|Авангардизм (ideology_vanguardist)]], [[tgr/Идеологии/Авангардизм (ideology_vanguardist_movement)|Авангардизм (ideology_vanguardist_movement)]], [[tgr/Идеологии/Авторитаризм|Авторитаризм]], [[tgr/Идеологии/Интегрализм|Интегрализм]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]], [[tgr/Идеологии/Фашизм (ideology_fascist_movement)|Фашизм (ideology_fascist_movement)]]
- **Идеологии** (lawgroup_legislative_process: strongly_disapprove): [[tgr/Идеологии/Анархизм|Анархизм]], [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Радикализм (ideology_radical)|Радикализм (ideology_radical)]], [[tgr/Идеологии/Радикализм (ideology_radical_movement)|Радикализм (ideology_radical_movement)]], [[tgr/Идеологии/Реформы|Реформы]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]

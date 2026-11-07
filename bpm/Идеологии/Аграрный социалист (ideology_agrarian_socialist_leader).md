---
type: concept
description: "Идеология «Аграрный социалист (ideology_agrarian_socialist_leader)» — BPM 1.13, `ideology_agrarian_socialist_leader`"
project: vic3
source: bpm
aliases: ["Аграрный социалист (ideology_agrarian_socialist_leader)", "Agrarian Socialist", "ideology_agrarian_socialist_leader"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_agrarian_socialist_leader
paths: [BPM/common/ideologies/bpm_leader_ideologies.txt]
---
# Аграрный социалист (ideology_agrarian_socialist_leader)

Идеология · `ideology_agrarian_socialist_leader` · `common/ideologies/bpm_leader_ideologies.txt:4822`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_Agrarian.dds`
- **character_ideology**: `yes`
- **show_in_list**: `yes`
- **lawgroup_distribution_of_power**:
  - [[bpm/Законы/Анархия|Анархия]] = `approve`
  - [[bpm/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_approve`
  - [[bpm/Законы/Имущественный ценз|Имущественный ценз]] = `disapprove`
  - [[bpm/Законы/Голосуют богатые|Голосуют богатые]] = `strongly_disapprove`
  - [[bpm/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `strongly_disapprove`
  - [[bpm/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[bpm/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[bpm/Законы/Технократия|Технократия]] = `disapprove`
  - [[bpm/Законы/Военная хунта|Военная хунта]] = `disapprove`
- **lawgroup_land_reform**:
  - [[bpm/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[bpm/Законы/Арендаторы|Арендаторы]] = `strongly_disapprove`
  - [[bpm/Законы/Крестьянское хозяйство|Крестьянское хозяйство]] = `approve`
  - [[bpm/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `strongly_approve`
  - [[bpm/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `disapprove`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `neutral`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `strongly_disapprove`
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `strongly_disapprove`
- **lawgroup_policing**:
  - [[bpm/Законы/Отсутствие формальной полиции|Отсутствие формальной полиции]] = `approve`
  - [[bpm/Законы/Только местная полиция|Только местная полиция]] = `disapprove`
  - [[bpm/Законы/Национальная полиция|Национальная полиция]] = `disapprove`
  - [[bpm/Законы/Милитаризованная полиция|Милитаризованная полиция]] = `strongly_disapprove`
  - [[bpm/Законы/Выборная полиция|Выборная полиция]] = `approve`
- **lawgroup_economic_system**:
  - [[bpm/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
  - [[bpm/Законы/Интервенционизм|Интервенционизм]] = `disapprove`
  - [[bpm/Законы/Аграрность|Аграрность]] = `approve`
  - [[bpm/Законы/Традиционализм|Традиционализм]] = `strongly_disapprove`
  - [[bpm/Законы/Свободная конкуренция|Свободная конкуренция]] = `disapprove`
  - [[bpm/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_approve`
  - [[bpm/Законы/Запрет промышленности|Запрет промышленности]] = `approve`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_repeatable_economy**:
  - [[bpm/Законы/Экономическая либерализация|Экономическая либерализация]] = `disapprove`
  - [[bpm/Законы/Сельскохозяйственные инвестиции|Сельскохозяйственные инвестиции]] = `strongly_approve`
  - [[bpm/Законы/Крестьянская повинность|Крестьянская повинность]] = `strongly_disapprove`
  - [[bpm/Законы/Общественные работы|Общественные работы]] = `neutral`
  - [[bpm/Законы/Принудительная индустриализация|Принудительная индустриализация]] = `strongly_disapprove`
- **interest_group_leader_trigger**: скрипт, строки 4882–4894
- **interest_group_leader_weight**: скрипт, строки 4896–4963
- **non_interest_group_leader_trigger**: скрипт, строки 4965–5008
- **non_interest_group_leader_weight**:
  - `value` = `10`

## Ссылаются

- **Группы интересов** (character_ideologies): [[bpm/Группы интересов/Анархисты|Анархисты]], [[bpm/Группы интересов/Реформистские социалисты|Реформистские социалисты]]

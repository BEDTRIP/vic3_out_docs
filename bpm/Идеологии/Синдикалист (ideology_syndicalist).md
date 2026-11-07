---
type: concept
description: "Идеология «Синдикалист (ideology_syndicalist)» — BPM 1.13, `ideology_syndicalist`"
project: vic3
source: bpm
aliases: ["Синдикалист (ideology_syndicalist)", "Syndicalist", "ideology_syndicalist"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_syndicalist
paths: [BPM/common/ideologies/bpm_leader_ideologies.txt]
---
# Синдикалист (ideology_syndicalist)

Идеология · `ideology_syndicalist` · `common/ideologies/bpm_leader_ideologies.txt:2811`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_communist.dds`
- **character_ideology**: `yes`
- **show_in_list**: `yes`
- **lawgroup_labor_rights**:
  - [[bpm/Законы/Защита прав рабочих|Защита прав рабочих]] = `strongly_approve`
  - [[bpm/Законы/Регулирующие органы|Регулирующие органы]] = `neutral`
  - [[bpm/Законы/Нет прав трудящихся|Нет прав трудящихся]] = `strongly_disapprove`
- **lawgroup_land_reform**:
  - [[bpm/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[bpm/Законы/Арендаторы|Арендаторы]] = `disapprove`
  - [[bpm/Законы/Крестьянское хозяйство|Крестьянское хозяйство]] = `neutral`
  - [[bpm/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `approve`
  - [[bpm/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `neutral`
- **lawgroup_distribution_of_power**:
  - [[bpm/Законы/Анархия|Анархия]] = `neutral`
  - [[bpm/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_approve`
  - [[bpm/Законы/Имущественный ценз|Имущественный ценз]] = `disapprove`
  - [[bpm/Законы/Голосуют богатые|Голосуют богатые]] = `strongly_disapprove`
  - [[bpm/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `strongly_disapprove`
  - [[bpm/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[bpm/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[bpm/Законы/Военная хунта|Военная хунта]] = `strongly_disapprove`
  - [[bpm/Законы/Технократия|Технократия]] = `disapprove`
- **lawgroup_economic_system**:
  - [[bpm/Законы/Традиционализм|Традиционализм]] = `strongly_disapprove`
  - [[bpm/Законы/Интервенционизм|Интервенционизм]] = `disapprove`
  - [[bpm/Законы/Аграрность|Аграрность]] = `strongly_disapprove`
  - [[bpm/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
  - [[bpm/Законы/Свободная конкуренция|Свободная конкуренция]] = `strongly_disapprove`
  - [[bpm/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_approve`
  - [[bpm/Законы/Командная экономика|Командная экономика]] = `approve`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `strongly_disapprove`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `strongly_disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `strongly_approve`
- **lawgroup_governance_principles**:
  - [[bpm/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[bpm/Законы/Республика (law_presidential_republic)|Республика (law_presidential_republic)]] = `approve`
  - [[bpm/Законы/Республика (law_parliamentary_republic)|Республика (law_parliamentary_republic)]] = `approve`
  - [[bpm/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[bpm/Законы/Советская республика|Советская республика]] = `strongly_approve`
- **lawgroup_labour_associations**:
  - [[bpm/Законы/Незаконные профсоюзы|Незаконные профсоюзы]] = `strongly_disapprove`
  - [[bpm/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `disapprove`
  - [[bpm/Законы/Ограниченные профсоюзы|Ограниченные профсоюзы]] = `disapprove`
  - [[bpm/Законы/Все профсоюзы разрешены|Все профсоюзы разрешены]] = `approve`
  - [[bpm/Законы/Только социалистические профсоюзы|Только социалистические профсоюзы]] = `disapprove`
  - [[bpm/Законы/Синдикализм|Синдикализм]] = `strongly_approve`
- **lawgroup_repeatable_economy**:
  - [[bpm/Законы/Экономическая либерализация|Экономическая либерализация]] = `disapprove`
  - [[bpm/Законы/Сельскохозяйственные инвестиции|Сельскохозяйственные инвестиции]] = `neutral`
  - [[bpm/Законы/Крестьянская повинность|Крестьянская повинность]] = `strongly_disapprove`
  - [[bpm/Законы/Общественные работы|Общественные работы]] = `approve`
  - [[bpm/Законы/Принудительная индустриализация|Принудительная индустриализация]] = `disapprove`
- **interest_group_leader_trigger**: скрипт, строки 2886–2910
- **interest_group_leader_weight**: скрипт, строки 2912–2980
- **non_interest_group_leader_trigger**: скрипт, строки 2982–3028
- **non_interest_group_leader_weight**:
  - `value` = `15`

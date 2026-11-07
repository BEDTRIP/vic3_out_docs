---
type: concept
description: "Идеология «Radical Abolitionist» — Hail Columbia 1.13, `ideology_usfp_abolitionist_radical`"
project: vic3
source: hail_columbia
aliases: ["Radical Abolitionist", "ideology_usfp_abolitionist_radical"]
tags: [hail_columbia, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_usfp_abolitionist_radical
paths: [for addon/Hail Columbia/common/ideologies/usfp_leader_ideologies.txt]
---
# Radical Abolitionist

Идеология · `ideology_usfp_abolitionist_radical` · `common/ideologies/usfp_leader_ideologies.txt:471`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_usfp_abolitionist_radical.dds`
- **character_ideology**: `yes`
- **lawgroup_slavery**:
  - [[hail_columbia/Законы/Запрет рабства|Запрет рабства]] = `strongly_approve`
  - [[hail_columbia/Законы/Унаследованное рабство|Унаследованное рабство]] = `strongly_disapprove`
  - [[hail_columbia/Законы/Долговое рабство|Долговое рабство]] = `strongly_disapprove`
  - [[hail_columbia/Законы/Работорговля|Работорговля]] = `strongly_disapprove`
  - [[hail_columbia/Законы/Колониальное рабство|Колониальное рабство]] = `strongly_disapprove`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `disapprove`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `neutral`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `neutral`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `neutral`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Подданство|Подданство]] = `disapprove`
  - [[hail_columbia/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `disapprove`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `strongly_approve`
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `neutral`
- **country_trigger**: скрипт, строки 501–508
- **interest_group_leader_trigger**: скрипт, строки 510–518
- **non_interest_group_leader_trigger**: скрипт, строки 520–530
- **interest_group_leader_weight**: скрипт, строки 533–592
- **non_interest_group_leader_weight**: скрипт, строки 594–613

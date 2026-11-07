---
type: concept
description: "Идеология «Земельный реформатор (ideology_land_reformer)» — ваниль 1.13, `ideology_land_reformer`"
project: vic3
source: vanilla
aliases: ["Земельный реформатор (ideology_land_reformer)", "Land Reformer", "ideology_land_reformer"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_land_reformer
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Земельный реформатор (ideology_land_reformer)

Идеология · `ideology_land_reformer` · `common/ideologies/01_character_ideologies.txt:8037`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_land_reformer.dds`
- **character_ideology**: `yes`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `strongly_disapprove`
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `neutral`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `neutral`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `neutral`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `neutral`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `neutral`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `approve`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `approve`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Огораживание|Огораживание]]
- **interest_group_leader_trigger**:
  - `ideology_land_reformer_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 8066–8083
- **interest_group_leader_weight**: скрипт, строки 8085–8207
- **non_interest_group_leader_weight**: скрипт, строки 8209–8302

---
type: concept
description: "Идеология «Феминизм (ideology_feminist)» — ваниль 1.13, `ideology_feminist`"
project: vic3
audience: agent
source: vanilla
aliases: ["Феминизм (ideology_feminist)", "Feminist", "ideology_feminist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_feminist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Феминизм (ideology_feminist)

Идеология · `ideology_feminist` · `common/ideologies/01_character_ideologies.txt:1944`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_womens_liberation.dds`
- **character_ideology**: `yes`
- **lawgroup_rights_of_women**:
  - [[vanilla/Законы/Женское избирательное право|Женское избирательное право]] = `strongly_approve`
  - [[vanilla/Законы/Женщины на рабочем месте|Женщины на рабочем месте]] = `neutral`
  - [[vanilla/Законы/Право собственности для женщин|Право собственности для женщин]] = `disapprove`
  - [[vanilla/Законы/Попечительство|Попечительство]] = `strongly_disapprove`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Феминизм|Феминизм]]
- **interest_group_leader_trigger**:
  - `ideology_feminist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 1964–1975
- **interest_group_leader_weight**: скрипт, строки 1977–2112
- **non_interest_group_leader_weight**: скрипт, строки 2114–2194

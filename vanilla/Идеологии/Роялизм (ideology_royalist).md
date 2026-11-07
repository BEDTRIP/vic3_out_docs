---
type: concept
description: "Идеология «Роялизм (ideology_royalist)» — ваниль 1.13, `ideology_royalist`"
project: vic3
source: vanilla
aliases: ["Роялизм (ideology_royalist)", "Royalist", "ideology_royalist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_royalist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Роялизм (ideology_royalist)

Идеология · `ideology_royalist` · `common/ideologies/01_character_ideologies.txt:3081`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_royalist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_approve`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `neutral`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `neutral`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `approve`
  - [[vanilla/Законы/Теократия|Теократия]] = `disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
- **country_trigger**: скрипт, строки 3096–3111
- **interest_group_leader_trigger**:
  - `ideology_royalist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 3117–3128
- **interest_group_leader_weight**: скрипт, строки 3130–3222
- **non_interest_group_leader_weight**: скрипт, строки 3224–3271

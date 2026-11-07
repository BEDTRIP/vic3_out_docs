---
type: concept
description: "Идеология «Нигилизм (ideology_nihilist)» — ваниль 1.13, `ideology_nihilist`"
project: vic3
audience: agent
source: vanilla
aliases: ["Нигилизм (ideology_nihilist)", "Nihilist", "ideology_nihilist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_nihilist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Нигилизм (ideology_nihilist)

Идеология · `ideology_nihilist` · `common/ideologies/01_character_ideologies.txt:536`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_nihilist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `neutral`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `neutral`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `disapprove`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `approve`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_disapprove`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `neutral`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_approve`
- **lawgroup_caste_hegemony**:
  - [[vanilla/Законы/Принудительная кастовая система|Принудительная кастовая система]] = `strongly_disapprove`
  - [[vanilla/Законы/Кодифицированная кастовая система|Кодифицированная кастовая система]] = `disapprove`
  - [[vanilla/Законы/Необязательная кастовая система|Необязательная кастовая система]] = `neutral`
  - [[vanilla/Законы/Позитивная дискриминация|Позитивная дискриминация]] = `neutral`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Реализм|Реализм]]
- **interest_group_leader_trigger**:
  - `ideology_nihilist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 573–600
- **interest_group_leader_weight**: скрипт, строки 602–743
- **non_interest_group_leader_weight**: скрипт, строки 745–849

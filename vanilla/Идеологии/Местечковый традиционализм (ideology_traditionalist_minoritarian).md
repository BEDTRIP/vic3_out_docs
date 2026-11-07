---
type: concept
description: "Идеология «Местечковый традиционализм (ideology_traditionalist_minoritarian)» — ваниль 1.13, `ideology_traditionalist_minoritarian`"
project: vic3
source: vanilla
aliases: ["Местечковый традиционализм (ideology_traditionalist_minoritarian)", "Minoritarian Traditionalist", "ideology_traditionalist_minoritarian"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_traditionalist_minoritarian
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Местечковый традиционализм (ideology_traditionalist_minoritarian)

Идеология · `ideology_traditionalist_minoritarian` · `common/ideologies/01_character_ideologies.txt:332`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_traditionalist.dds`
- **character_ideology**: `yes`
- **lawgroup_rights_of_women**:
  - [[vanilla/Законы/Попечительство|Попечительство]] = `approve`
  - [[vanilla/Законы/Право собственности для женщин|Право собственности для женщин]] = `neutral`
  - [[vanilla/Законы/Женщины на рабочем месте|Женщины на рабочем месте]] = `disapprove`
  - [[vanilla/Законы/Женское избирательное право|Женское избирательное право]] = `strongly_disapprove`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_disapprove`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `approve`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `neutral`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `approve`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `neutral`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `neutral`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `disapprove`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
- **lawgroup_caste_hegemony**:
  - [[vanilla/Законы/Принудительная кастовая система|Принудительная кастовая система]] = `strongly_approve`
  - [[vanilla/Законы/Кодифицированная кастовая система|Кодифицированная кастовая система]] = `approve`
  - [[vanilla/Законы/Необязательная кастовая система|Необязательная кастовая система]] = `disapprove`
  - [[vanilla/Законы/Позитивная дискриминация|Позитивная дискриминация]] = `strongly_disapprove`
- **lawgroup_edo_social_system**:
  - [[vanilla/Законы/Строгая сословная иерархия|Строгая сословная иерархия]] = `strongly_approve`
  - [[vanilla/Законы/Смягчённая сословная иерархия|Смягчённая сословная иерархия]] = `disapprove`
  - [[vanilla/Законы/Гибкая сословная иерархия|Гибкая сословная иерархия]] = `strongly_disapprove`
- **interest_group_leader_trigger**:
  - `ideology_traditionalist_minoritarian_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 377–394
- **interest_group_leader_weight**: скрипт, строки 396–479
- **non_interest_group_leader_weight**: скрипт, строки 481–533

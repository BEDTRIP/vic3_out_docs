---
type: concept
description: "Идеология «Традиционализм (ideology_traditionalist)» — ваниль 1.13, `ideology_traditionalist`"
project: vic3
audience: agent
source: vanilla
aliases: ["Традиционализм (ideology_traditionalist)", "Traditionalist", "ideology_traditionalist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_traditionalist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Традиционализм (ideology_traditionalist)

Идеология · `ideology_traditionalist` · `common/ideologies/01_character_ideologies.txt:126`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_traditionalist.dds`
- **character_ideology**: `yes`
- **lawgroup_rights_of_women**:
  - [[vanilla/Законы/Попечительство|Попечительство]] = `approve`
  - [[vanilla/Законы/Право собственности для женщин|Право собственности для женщин]] = `neutral`
  - [[vanilla/Законы/Женщины на рабочем месте|Женщины на рабочем месте]] = `disapprove`
  - [[vanilla/Законы/Женское избирательное право|Женское избирательное право]] = `strongly_disapprove`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `approve`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_disapprove`
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
- **country_trigger**: скрипт, строки 167–171
- **interest_group_leader_trigger**:
  - `ideology_traditionalist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 177–190
- **interest_group_leader_weight**: скрипт, строки 192–275
- **non_interest_group_leader_weight**: скрипт, строки 277–329

## Ссылаются

- **Группы интересов** (character_ideologies): [[vanilla/Группы интересов/Верующие|Верующие]], [[vanilla/Группы интересов/Землевладельцы|Землевладельцы]], [[vanilla/Группы интересов/Мелкие буржуа|Мелкие буржуа]]

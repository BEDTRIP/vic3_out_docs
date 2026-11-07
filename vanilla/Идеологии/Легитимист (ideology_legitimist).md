---
type: concept
description: "Идеология «Легитимист (ideology_legitimist)» — ваниль 1.13, `ideology_legitimist`"
project: vic3
source: vanilla
aliases: ["Легитимист (ideology_legitimist)", "Legitimist", "ideology_legitimist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_legitimist
paths: [.vanillaVIC3/common/ideologies/02_character_french_flavored.txt]
---
# Легитимист (ideology_legitimist)

Идеология · `ideology_legitimist` · `common/ideologies/02_character_french_flavored.txt:291`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_legitimist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_approve`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `neutral`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `approve`
  - [[vanilla/Законы/Теократия|Теократия]] = `disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_approve`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `neutral`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `strongly_disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `strongly_disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `strongly_disapprove`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `approve`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_disapprove`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_disapprove`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `disapprove`
  - [[vanilla/Законы/Цензура|Цензура]] = `approve`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_approve`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `neutral`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `approve`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `neutral`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `neutral`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `disapprove`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
- **country_trigger**: скрипт, строки 341–360
- **interest_group_leader_trigger**:
  - `ideology_legitimist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 366–369
- **interest_group_leader_weight**: скрипт, строки 371–473
- **non_interest_group_leader_weight**: скрипт, строки 475–558

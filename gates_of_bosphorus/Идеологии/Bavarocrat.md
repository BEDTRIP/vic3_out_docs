---
type: concept
description: "Идеология «Bavarocrat» — Gates of Bosphorus 1.13, `ideology_gbbf_bavarocrat`"
project: vic3
source: gates_of_bosphorus
aliases: ["Bavarocrat", "ideology_gbbf_bavarocrat"]
tags: [gates_of_bosphorus, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_gbbf_bavarocrat
paths: [for addon/gatesofbosphorus/common/ideologies/gbbf_leader_ideologies.txt]
---
# Bavarocrat

Идеология · `ideology_gbbf_bavarocrat` · `common/ideologies/gbbf_leader_ideologies.txt:1`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_gbbf_bavarocrat.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_approve`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Теократия|Теократия]] = `disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_approve`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `approve`
  - [[vanilla/Законы/Технократия|Технократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `neutral`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_approve`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_disapprove`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_policing**:
  - [[vanilla/Законы/Местная полиция|Местная полиция]] = `strongly_approve`
  - [[vanilla/Законы/Профессиональная полиция|Профессиональная полиция]] = `neutral`
  - [[vanilla/Законы/Военизированная полиция|Военизированная полиция]] = `approve`
  - [[vanilla/Законы/Нет полиции|Нет полиции]] = `approve`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `approve`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `approve`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `disapprove`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `neutral`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `approve`
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `approve`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `disapprove`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `strongly_disapprove`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_disapprove`
- **country_trigger**: скрипт, строки 49–51
- **interest_group_leader_trigger**: скрипт, строки 52–69
- **interest_group_leader_weight**: скрипт, строки 70–92
- **non_interest_group_leader_weight**:
  - `value` = `0`

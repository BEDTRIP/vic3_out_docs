---
type: concept
description: "Идеология «Metaxist (ideology_gbbf_metaxist_leader)» — Gates of Bosphorus 1.15, `ideology_gbbf_metaxist_leader`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Metaxist (ideology_gbbf_metaxist_leader)", "Metaxist", "ideology_gbbf_metaxist_leader"]
tags: [gates_of_bosphorus, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_gbbf_metaxist_leader
paths: [for addon/gatesofbosphorus/common/ideologies/gbbf_leader_ideologies.txt]
---
# Metaxist (ideology_gbbf_metaxist_leader)

Идеология · `ideology_gbbf_metaxist_leader` · `common/ideologies/gbbf_leader_ideologies.txt:847`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_fascist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Теократия|Теократия]] = `disapprove`
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_approve`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `neutral`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `strongly_approve`
  - [[vanilla/Законы/Автократия|Автократия]] = `approve`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `neutral`
  - [[vanilla/Законы/Технократия|Технократия]] = `neutral`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `approve`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `strongly_disapprove`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `strongly_disapprove`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `disapprove`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `disapprove`
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `strongly_approve`
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `strongly_disapprove`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `strongly_approve`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `approve`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `disapprove`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `strongly_disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_disapprove`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `disapprove`
  - [[vanilla/Законы/Цензура|Цензура]] = `neutral`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_approve`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `neutral`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `approve`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `approve`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `strongly_approve`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `disapprove`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
- **country_trigger**:
  - `country_has_primary_culture` = `cu:greek`
  - `has_global_variable` = `grefm_venizelos_has_landed`
  - `has_technology_researched` = [[vanilla/Технологии/Политическая агитация|Политическая агитация]]
- **interest_group_leader_trigger**: скрипт, строки 908–912
- **interest_group_leader_weight**: скрипт, строки 913–1100
- **non_interest_group_leader_trigger**: скрипт, строки 1101–1105
- **non_interest_group_leader_weight**: скрипт, строки 1106–1270

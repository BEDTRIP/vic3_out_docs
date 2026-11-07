---
type: concept
description: "Идеология «Радикализм (ideology_radical)» — ваниль 1.13, `ideology_radical`"
project: vic3
source: vanilla
aliases: ["Радикализм (ideology_radical)", "Radical", "ideology_radical"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_radical
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Радикализм (ideology_radical)

Идеология · `ideology_radical` · `common/ideologies/01_character_ideologies.txt:1176`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_radical.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `neutral`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `approve`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `disapprove`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `strongly_disapprove`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `strongly_approve`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `approve`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `neutral`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_approve`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `approve`
  - [[vanilla/Законы/Цензура|Цензура]] = `disapprove`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `strongly_disapprove`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Гарантия свобод|Гарантия свобод]] = `strongly_approve`
  - [[vanilla/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `neutral`
  - [[vanilla/Законы/Национальная гвардия|Национальная гвардия]] = `approve`
  - [[vanilla/Законы/Тайная полиция|Тайная полиция]] = `strongly_disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `approve`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `neutral`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `disapprove`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `disapprove`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `neutral`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `disapprove`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `neutral`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`
- **lawgroup_edo_social_system**:
  - [[vanilla/Законы/Строгая сословная иерархия|Строгая сословная иерархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Смягчённая сословная иерархия|Смягчённая сословная иерархия]] = `disapprove`
  - [[vanilla/Законы/Гибкая сословная иерархия|Гибкая сословная иерархия]] = `approve`
- **country_trigger**: скрипт, строки 1239–1258
- **interest_group_leader_trigger**:
  - `ideology_radical_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 1264–1292
- **interest_group_leader_weight**: скрипт, строки 1294–1527
- **non_interest_group_leader_weight**: скрипт, строки 1529–1689

## Ссылаются

- **Группы интересов** (character_ideologies): [[vanilla/Группы интересов/Интеллигенты|Интеллигенты]], [[vanilla/Группы интересов/Профсоюзы|Профсоюзы]]

---
type: concept
description: "Идеология «Коммунизм (ideology_communist_leader)» — ваниль 1.15, `ideology_communist_leader`"
project: vic3
audience: agent
source: vanilla
aliases: ["Коммунизм (ideology_communist_leader)", "Communist", "ideology_communist_leader"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_communist_leader
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Коммунизм (ideology_communist_leader)

Идеология · `ideology_communist_leader` · `common/ideologies/01_character_ideologies.txt:3790`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_communist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `approve`
- **lawgroup_distribution_of_power**:
  - [[vanilla/Законы/Олигархия|Олигархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Автократия|Автократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Анархия|Анархия]] = `neutral`
  - [[vanilla/Законы/Всеобщее избирательное право|Всеобщее избирательное право]] = `disapprove`
  - [[vanilla/Законы/Имущественный ценз|Имущественный ценз]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют богатые|Голосуют богатые]] = `strongly_disapprove`
  - [[vanilla/Законы/Голосуют землевладельцы|Голосуют землевладельцы]] = `strongly_disapprove`
  - [[vanilla/Законы/Технократия|Технократия]] = `disapprove`
  - [[vanilla/Законы/Однопартийное государство|Однопартийное государство]] = `disapprove`
  - [[vanilla/Законы/Рабочий ценз|Рабочий ценз]] = `approve`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_disapprove`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `neutral`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `approve`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `disapprove`
  - [[vanilla/Законы/Военные чиновники|Военные чиновники]] = `strongly_disapprove`
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `disapprove`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `strongly_disapprove`
  - [[vanilla/Законы/Общественная администрация|Общественная администрация]] = `approve`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `neutral`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `disapprove`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `neutral`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `strongly_disapprove`
  - [[vanilla/Законы/Революционная гвардия|Революционная гвардия]] = `approve`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `strongly_disapprove`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `disapprove`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `strongly_disapprove`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `neutral`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `approve`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Социализм|Социализм]]
- **interest_group_leader_trigger**:
  - `ideology_communist_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 3858–3882
- **interest_group_leader_weight**: скрипт, строки 3884–4188
- **non_interest_group_leader_weight**: скрипт, строки 4190–4414

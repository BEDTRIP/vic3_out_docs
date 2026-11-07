---
type: concept
description: "Идеология «Коммунизм (ideology_communist)» — ваниль 1.13, `ideology_communist`"
project: vic3
source: vanilla
aliases: ["Коммунизм (ideology_communist)", "Communist", "ideology_communist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_communist
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Коммунизм (ideology_communist)

Идеология · `ideology_communist` · `common/ideologies/01_character_ideologies.txt:3597`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_communist.dds`
- **character_ideology**: `yes`
- **lawgroup_labor_rights**:
  - [[vanilla/Законы/Защита прав рабочих|Защита прав рабочих]] = `strongly_approve`
  - [[vanilla/Законы/Регулирующие органы|Регулирующие органы]] = `approve`
  - [[vanilla/Законы/Нет прав трудящихся|Нет прав трудящихся]] = `neutral`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Монархия|Монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `disapprove`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `disapprove`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `strongly_disapprove`
  - [[vanilla/Законы/Теократия|Теократия]] = `strongly_disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_approve`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_approve`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_approve`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `neutral`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `disapprove`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `disapprove`
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `strongly_disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_church_and_state**:
  - [[vanilla/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `strongly_disapprove`
  - [[vanilla/Законы/Свобода совести|Свобода совести]] = `disapprove`
  - [[vanilla/Законы/Полное разделение|Полное разделение]] = `neutral`
  - [[vanilla/Законы/Государственный атеизм|Государственный атеизм]] = `approve`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `disapprove`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `neutral`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `approve`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `disapprove`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `neutral`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `strongly_disapprove`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `neutral`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `approve`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Социализм|Социализм]]
- **interest_group_leader_trigger**:
  - `ideology_communist_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 3661–3685
- **interest_group_leader_weight**: скрипт, строки 3687–3875
- **non_interest_group_leader_weight**: скрипт, строки 3877–4007

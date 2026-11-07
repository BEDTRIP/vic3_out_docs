---
type: concept
description: "Идеология «Self-Strengthening Reformer (ideology_westernlism_leader)» — VC 1.13, `ideology_westernlism_leader`"
project: vic3
source: vc
aliases: ["Self-Strengthening Reformer (ideology_westernlism_leader)", "Self-Strengthening Reformer", "ideology_westernlism_leader"]
tags: [VC, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_westernlism_leader
paths: [VC/common/ideologies/joi_leader_ideologies.txt]
---
# Self-Strengthening Reformer (ideology_westernlism_leader)

Идеология · `ideology_westernlism_leader` · `common/ideologies/joi_leader_ideologies.txt:162`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/idealogy_leader_modernizer.dds`
- **character_ideology**: `yes`
- **lawgroup_economic_system**:
  - [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]] = `neutral`
  - [[vanilla/Законы/Интервенционизм|Интервенционизм]] = `approve`
  - [[vanilla/Законы/Аграрность|Аграрность]] = `neutral`
  - [[vanilla/Законы/Традиционализм|Традиционализм]] = `disapprove`
  - [[vanilla/Законы/Кооперативное владение|Кооперативное владение]] = `strongly_disapprove`
  - [[vanilla/Законы/Командная экономика|Командная экономика]] = `strongly_disapprove`
  - [[vanilla/Законы/Запрет промышленности|Запрет промышленности]] = `disapprove`
  - [[vanilla/Законы/Добывающая экономика|Добывающая экономика]] = `strongly_disapprove`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `disapprove`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `approve`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `neutral`
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `approve`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `disapprove`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `neutral`
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `approve`
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `neutral`
- **lawgroup_land_reform**:
  - [[vanilla/Законы/Крепостное право|Крепостное право]] = `strongly_disapprove`
  - [[vanilla/Законы/Арендаторы|Арендаторы]] = `neutral`
  - [[vanilla/Законы/Крестьянское землевладение|Крестьянское землевладение]] = `neutral`
  - [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]] = `neutral`
  - [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]] = `neutral`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Частные школы|Частные школы]] = `approve`
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `approve`
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `neutral`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `neutral`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `neutral`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `approve`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `neutral`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `disapprove`
- **lawgroup_navy_model**:
  - [[vanilla/Законы/Торговый флот|Торговый флот]] = `disapprove`
  - [[vanilla/Законы/Молодая школа|Молодая школа]] = `approve`
  - [[vanilla/Законы/Флот крупных кораблей|Флот крупных кораблей]] = `neutral`
  - [[vanilla/Законы/Дипломатический флот|Дипломатический флот]] = `approve`
- **interest_group_leader_trigger**: скрипт, строки 222–246
- **country_trigger**: скрипт, строки 248–252
- **non_interest_group_leader_trigger**:
  - `ideology_traditionalist_valid_trigger` = `yes`
- **interest_group_leader_weight**: скрипт, строки 258–281
- **non_interest_group_leader_weight**:
  - `value` = `250`

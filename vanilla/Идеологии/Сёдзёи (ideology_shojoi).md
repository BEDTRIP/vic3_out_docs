---
type: concept
description: "Идеология «Сёдзёи (ideology_shojoi)» — ваниль 1.15, `ideology_shojoi`"
project: vic3
audience: agent
source: vanilla
aliases: ["Сёдзёи (ideology_shojoi)", "Shōjōi", "ideology_shojoi"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_shojoi
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Сёдзёи (ideology_shojoi)

Идеология · `ideology_shojoi` · `common/ideologies/01_character_ideologies.txt:12994`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/isolationist.dds`
- **character_ideology**: `yes`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `strongly_approve`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `approve`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `neutral`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `disapprove`
  - [[vanilla/Законы/Революционная гвардия|Революционная гвардия]] = `strongly_disapprove`
- **lawgroup_navy_model**:
  - [[vanilla/Законы/Торговый флот|Торговый флот]] = `disapprove`
  - [[vanilla/Законы/Молодая школа|Молодая школа]] = `approve`
  - [[vanilla/Законы/Флот крупных кораблей|Флот крупных кораблей]] = `neutral`
  - [[vanilla/Законы/Дипломатический флот|Дипломатический флот]] = `neutral`
- **lawgroup_trade_policy**:
  - [[vanilla/Законы/Свободная торговля|Свободная торговля]] = `strongly_disapprove`
  - [[vanilla/Законы/Меркантилизм|Меркантилизм]] = `disapprove`
  - [[vanilla/Законы/Протекционизм|Протекционизм]] = `disapprove`
  - [[vanilla/Законы/Изоляционизм|Изоляционизм]] = `approve`
- **lawgroup_migration**:
  - [[vanilla/Законы/Закрытые границы|Закрытые границы]] = `approve`
  - [[vanilla/Законы/Миграционный контроль|Миграционный контроль]] = `disapprove`
  - [[vanilla/Законы/Миграция не контролируется|Миграция не контролируется]] = `strongly_disapprove`
- **country_trigger**: скрипт, строки 13027–13031
- **interest_group_leader_trigger**:
  - `ideology_shojoi_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 13037–13046
- **interest_group_leader_weight**: скрипт, строки 13048–13117
- **non_interest_group_leader_weight**: скрипт, строки 13119–13149

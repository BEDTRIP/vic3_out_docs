---
type: concept
description: "Идеология «Джингоизм (ideology_jingoist_leader)» — ваниль 1.13, `ideology_jingoist_leader`"
project: vic3
audience: agent
source: vanilla
aliases: ["Джингоизм (ideology_jingoist_leader)", "Jingoist", "ideology_jingoist_leader"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_jingoist_leader
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Джингоизм (ideology_jingoist_leader)

Идеология · `ideology_jingoist_leader` · `common/ideologies/01_character_ideologies.txt:2810`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_jingoist.dds`
- **character_ideology**: `yes`
- **lawgroup_army_model**:
  - [[vanilla/Законы/Массовый призыв|Массовый призыв]] = `strongly_approve`
  - [[vanilla/Законы/Профессиональная армия|Профессиональная армия]] = `approve`
  - [[vanilla/Законы/Национальное ополчение|Национальное ополчение]] = `neutral`
  - [[vanilla/Законы/Крестьянское ополчение|Крестьянское ополчение]] = `disapprove`
- **lawgroup_navy_model**:
  - [[vanilla/Законы/Торговый флот|Торговый флот]] = `strongly_disapprove`
  - [[vanilla/Законы/Молодая школа|Молодая школа]] = `neutral`
  - [[vanilla/Законы/Флот крупных кораблей|Флот крупных кораблей]] = `strongly_approve`
  - [[vanilla/Законы/Дипломатический флот|Дипломатический флот]] = `approve`
- **lawgroup_colonization**:
  - [[vanilla/Законы/Нет колоний|Нет колоний]] = `neutral`
  - [[vanilla/Законы/Переселение в колонии|Переселение в колонии]] = `approve`
  - [[vanilla/Законы/Колонизация границ|Колонизация границ]] = `approve`
  - [[vanilla/Законы/Колониальная эксплуатация|Колониальная эксплуатация]] = `strongly_approve`
- **interest_group_leader_trigger**:
  - `ideology_jingoist_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 2840–2852
- **interest_group_leader_weight**: скрипт, строки 2854–2986
- **non_interest_group_leader_weight**: скрипт, строки 2988–3078

## Ссылаются

- **Группы интересов** (character_ideologies): [[vanilla/Группы интересов/Мелкие буржуа|Мелкие буржуа]]

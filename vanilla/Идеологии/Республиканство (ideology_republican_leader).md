---
type: concept
description: "Идеология «Республиканство (ideology_republican_leader)» — ваниль 1.15, `ideology_republican_leader`"
project: vic3
audience: agent
source: vanilla
aliases: ["Республиканство (ideology_republican_leader)", "Republican", "ideology_republican_leader"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_republican_leader
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Республиканство (ideology_republican_leader)

Идеология · `ideology_republican_leader` · `common/ideologies/01_character_ideologies.txt:925`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_republican.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `strongly_approve`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `approve`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `neutral`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `disapprove`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `disapprove`
  - [[vanilla/Законы/Монархия|Монархия]] = `disapprove`
  - [[vanilla/Законы/Теократия|Теократия]] = `disapprove`
- **lawgroup_bureaucracy**:
  - [[vanilla/Законы/Избираемые чиновники|Избираемые чиновники]] = `approve`
  - [[vanilla/Законы/Военные чиновники|Военные чиновники]] = `neutral`
  - [[vanilla/Законы/Назначаемые чиновники|Назначаемые чиновники]] = `neutral`
  - [[vanilla/Законы/Потомственные чиновники|Потомственные чиновники]] = `disapprove`
  - [[vanilla/Законы/Общественная администрация|Общественная администрация]] = `disapprove`
- **interest_group_leader_trigger**:
  - `ideology_republican_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 952–978
- **interest_group_leader_weight**: скрипт, строки 980–1147
- **non_interest_group_leader_weight**: скрипт, строки 1149–1258

## Ссылаются

- **Группы интересов** (character_ideologies): [[vanilla/Группы интересов/Интеллигенты|Интеллигенты]]

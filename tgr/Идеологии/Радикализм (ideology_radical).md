---
type: concept
description: "Идеология «Радикализм (ideology_radical)» — TGR 1.13, `ideology_radical`"
project: vic3
audience: agent
source: tgr
aliases: ["Радикализм (ideology_radical)", "Radical", "ideology_radical"]
tags: [TGR, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_radical
paths: [TheGreatRevision/common/ideologies/TGR_POLITICS_character_ideologies.txt]
replaces: "[[vanilla/Идеологии/Радикализм (ideology_radical)]]"
---
# Радикализм (ideology_radical)

Идеология · `ideology_radical` · `common/ideologies/TGR_POLITICS_character_ideologies.txt:57` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **lawgroup_election_system**: добавлено вставкой
- **lawgroup_legislative_process**: добавлено вставкой

## Поля

- **lawgroup_election_system**:
  - [[tgr/Законы/No Elections|No Elections]] = `disapprove`
  - [[tgr/Законы/Proportional System|Proportional System]] = `strongly_approve`
  - [[tgr/Законы/Majoritarian System|Majoritarian System]] = `disapprove`
  - [[tgr/Законы/Mixed System|Mixed System]] = `neutral`
  - [[tgr/Законы/Ranked System|Ranked System]] = `approve`
- **lawgroup_legislative_process**:
  - [[tgr/Законы/Advisory Parliament Only|Advisory Parliament Only]] = `strongly_disapprove`
  - [[tgr/Законы/Restricted Parliamentary Authority|Restricted Parliamentary Authority]] = `disapprove`
  - [[tgr/Законы/Balance of Powers|Balance of Powers]] = `neutral`
  - [[tgr/Законы/Unicameral Parliamentary System|Unicameral Parliamentary System]] = `approve`
  - [[tgr/Законы/Bicameral Parliamentary System|Bicameral Parliamentary System]] = `strongly_approve`

## Ссылаются

- **Группы интересов** (character_ideologies): [[tgr/Группы интересов/Интеллигенты|Интеллигенты]], [[tgr/Группы интересов/Профсоюзы|Профсоюзы]]

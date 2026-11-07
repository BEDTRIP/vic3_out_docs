---
type: concept
description: "Идеология «Радикализм (ideology_radical_movement)» — TGR 1.13, `ideology_radical_movement`"
project: vic3
source: tgr
aliases: ["Радикализм (ideology_radical_movement)", "Radical", "ideology_radical_movement"]
tags: [TGR, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_radical_movement
paths: [TheGreatRevision/common/ideologies/TGR_POLITICS_ig_ideologies_movement.txt]
replaces: "[[vanilla/Идеологии/Радикализм (ideology_radical_movement)]]"
---
# Радикализм (ideology_radical_movement)

Идеология · `ideology_radical_movement` · `common/ideologies/TGR_POLITICS_ig_ideologies_movement.txt:339` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **lawgroup_election_system**: добавлено вставкой
- **lawgroup_legislative_process**: добавлено вставкой
- **lawgroup_taxation**: добавлено вставкой

## Поля

- **lawgroup_election_system**:
  - [[tgr/Законы/No Elections|No Elections]] = `disapprove`
  - [[tgr/Законы/Proportional System|Proportional System]] = `strongly_approve`
  - [[tgr/Законы/Majoritarian System|Majoritarian System]] = `neutral`
  - [[tgr/Законы/Mixed System|Mixed System]] = `approve`
  - [[tgr/Законы/Ranked System|Ranked System]] = `approve`
- **lawgroup_legislative_process**:
  - [[tgr/Законы/Advisory Parliament Only|Advisory Parliament Only]] = `strongly_disapprove`
  - [[tgr/Законы/Restricted Parliamentary Authority|Restricted Parliamentary Authority]] = `disapprove`
  - [[tgr/Законы/Balance of Powers|Balance of Powers]] = `neutral`
  - [[tgr/Законы/Unicameral Parliamentary System|Unicameral Parliamentary System]] = `approve`
  - [[tgr/Законы/Bicameral Parliamentary System|Bicameral Parliamentary System]] = `strongly_approve`
- **lawgroup_taxation**:
  - [[tgr/Законы/Налог на душу населения|Налог на душу населения]] = `disapprove`
  - [[tgr/Законы/Земельное налогообложение|Земельное налогообложение]] = `neutral`
  - [[tgr/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[tgr/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `disapprove`
  - [[tgr/Законы/Прогрессивный налог|Прогрессивный налог]] = `neutral`

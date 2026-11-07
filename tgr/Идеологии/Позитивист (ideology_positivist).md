---
type: concept
description: "Идеология «Позитивист (ideology_positivist)» — TGR 1.13, `ideology_positivist`"
project: vic3
audience: agent
source: tgr
aliases: ["Позитивист (ideology_positivist)", "Positivist", "ideology_positivist"]
tags: [TGR, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_positivist
paths: [TheGreatRevision/common/ideologies/TGR_POLITICS_character_ideologies.txt]
replaces: "[[vanilla/Идеологии/Позитивист (ideology_positivist)]]"
---
# Позитивист (ideology_positivist)

Идеология · `ideology_positivist` · `common/ideologies/TGR_POLITICS_character_ideologies.txt:591` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **lawgroup_election_system**: добавлено вставкой
- **lawgroup_legislative_process**: добавлено вставкой

## Поля

- **lawgroup_election_system**:
  - [[tgr/Законы/No Elections|No Elections]] = `disapprove`
  - [[tgr/Законы/Proportional System|Proportional System]] = `strongly_disapprove`
  - [[tgr/Законы/Majoritarian System|Majoritarian System]] = `approve`
  - [[tgr/Законы/Mixed System|Mixed System]] = `disapprove`
  - [[tgr/Законы/Ranked System|Ranked System]] = `approve`
- **lawgroup_legislative_process**:
  - [[tgr/Законы/Advisory Parliament Only|Advisory Parliament Only]] = `neutral`
  - [[tgr/Законы/Restricted Parliamentary Authority|Restricted Parliamentary Authority]] = `approve`
  - [[tgr/Законы/Balance of Powers|Balance of Powers]] = `neutral`
  - [[tgr/Законы/Unicameral Parliamentary System|Unicameral Parliamentary System]] = `disapprove`
  - [[tgr/Законы/Bicameral Parliamentary System|Bicameral Parliamentary System]] = `disapprove`

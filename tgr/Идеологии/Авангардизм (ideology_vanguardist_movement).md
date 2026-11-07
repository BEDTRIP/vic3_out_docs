---
type: concept
description: "Идеология «Авангардизм (ideology_vanguardist_movement)» — TGR 1.13, `ideology_vanguardist_movement`"
project: vic3
audience: agent
source: tgr
aliases: ["Авангардизм (ideology_vanguardist_movement)", "Vanguardist", "ideology_vanguardist_movement"]
tags: [TGR, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_vanguardist_movement
paths: [TheGreatRevision/common/ideologies/TGR_POLITICS_ig_ideologies_movement.txt]
replaces: "[[vanilla/Идеологии/Авангардизм (ideology_vanguardist_movement)]]"
---
# Авангардизм (ideology_vanguardist_movement)

Идеология · `ideology_vanguardist_movement` · `common/ideologies/TGR_POLITICS_ig_ideologies_movement.txt:150` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **lawgroup_election_system**: добавлено вставкой
- **lawgroup_legislative_process**: добавлено вставкой
- **lawgroup_centralization**: добавлено вставкой

## Поля

- **lawgroup_election_system**:
  - [[tgr/Законы/No Elections|No Elections]] = `strongly_approve`
  - [[tgr/Законы/Proportional System|Proportional System]] = `disapprove`
  - [[tgr/Законы/Majoritarian System|Majoritarian System]] = `approve`
  - [[tgr/Законы/Mixed System|Mixed System]] = `neutral`
  - [[tgr/Законы/Ranked System|Ranked System]] = `disapprove`
- **lawgroup_legislative_process**:
  - [[tgr/Законы/Advisory Parliament Only|Advisory Parliament Only]] = `strongly_approve`
  - [[tgr/Законы/Restricted Parliamentary Authority|Restricted Parliamentary Authority]] = `approve`
  - [[tgr/Законы/Balance of Powers|Balance of Powers]] = `neutral`
  - [[tgr/Законы/Unicameral Parliamentary System|Unicameral Parliamentary System]] = `disapprove`
  - [[tgr/Законы/Bicameral Parliamentary System|Bicameral Parliamentary System]] = `strongly_disapprove`
- **lawgroup_centralization**:
  - [[tgr/Законы/Economic Decentralization|Economic Decentralization]] = `disapprove`
  - [[tgr/Законы/Administrative Decentralization|Administrative Decentralization]] = `disapprove`
  - [[tgr/Законы/Local Autonomies|Local Autonomies]] = `neutral`
  - [[tgr/Законы/Administrative Centralization|Administrative Centralization]] = `approve`
  - [[tgr/Законы/Economic Centralization|Economic Centralization]] = `strongly_approve`

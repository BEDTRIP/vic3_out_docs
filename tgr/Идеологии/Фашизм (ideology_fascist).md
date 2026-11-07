---
type: concept
description: "Идеология «Фашизм (ideology_fascist)» — TGR 1.13, `ideology_fascist`"
project: vic3
source: tgr
aliases: ["Фашизм (ideology_fascist)", "Fascist", "ideology_fascist"]
tags: [TGR, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_fascist
paths: [TheGreatRevision/common/ideologies/TGR_POLITICS_character_ideologies.txt]
replaces: "[[vanilla/Идеологии/Фашизм (ideology_fascist)]]"
---
# Фашизм (ideology_fascist)

Идеология · `ideology_fascist` · `common/ideologies/TGR_POLITICS_character_ideologies.txt:331` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **lawgroup_election_system**: добавлено вставкой
- **lawgroup_legislative_process**: добавлено вставкой
- **lawgroup_foreign_policy**: добавлено вставкой
- **lawgroup_economic_incentives_tertiary**: добавлено вставкой
- **lawgroup_economic_incentives_public**: добавлено вставкой
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
  - [[tgr/Законы/Balance of Powers|Balance of Powers]] = `disapprove`
  - [[tgr/Законы/Unicameral Parliamentary System|Unicameral Parliamentary System]] = `strongly_disapprove`
  - [[tgr/Законы/Bicameral Parliamentary System|Bicameral Parliamentary System]] = `strongly_disapprove`
- **lawgroup_foreign_policy**:
  - [[tgr/Законы/No Specific Focus|No Specific Focus]] = `neutral`
  - [[tgr/Законы/Reinforces Foreign perception|Reinforces Foreign perception]] = `approve`
  - [[tgr/Законы/Military Expansionism|Military Expansionism]] = `approve`
  - [[tgr/Законы/National Sovranism|National Sovranism]] = `strongly_approve`
  - [[tgr/Законы/Spread Socialist Ideas|Spread Socialist Ideas]] = `disapprove`
- **lawgroup_economic_incentives_tertiary**:
  - [[tgr/Законы/Manufacturing Investments|Manufacturing Investments]] = `neutral`
  - [[tgr/Законы/Light Industry Investments|Light Industry Investments]] = `approve`
  - [[tgr/Законы/Heavy Industry Investments|Heavy Industry Investments]] = `strongly_approve`
- **lawgroup_economic_incentives_public**:
  - [[tgr/Законы/No Incentive Focus (economic_incentives_no_focus_public)|No Incentive Focus (economic_incentives_no_focus_public)]] = `neutral`
  - [[tgr/Законы/Military Sector Investments|Military Sector Investments]] = `approve`
- **lawgroup_centralization**:
  - [[tgr/Законы/Economic Decentralization|Economic Decentralization]] = `strongly_disapprove`
  - [[tgr/Законы/Administrative Decentralization|Administrative Decentralization]] = `disapprove`
  - [[tgr/Законы/Local Autonomies|Local Autonomies]] = `neutral`
  - [[tgr/Законы/Administrative Centralization|Administrative Centralization]] = `approve`
  - [[tgr/Законы/Economic Centralization|Economic Centralization]] = `strongly_approve`

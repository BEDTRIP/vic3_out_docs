---
type: concept
description: "Идеология «Либерализм (ideology_liberal_leader)» — TGR 1.13, `ideology_liberal_leader`"
project: vic3
audience: agent
source: tgr
aliases: ["Либерализм (ideology_liberal_leader)", "Liberal", "ideology_liberal_leader"]
tags: [TGR, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_liberal_leader
paths: [TheGreatRevision/common/ideologies/TGR_POLITICS_character_ideologies.txt]
replaces: "[[vanilla/Идеологии/Либерализм (ideology_liberal_leader)]]"
---
# Либерализм (ideology_liberal_leader)

Идеология · `ideology_liberal_leader` · `common/ideologies/TGR_POLITICS_character_ideologies.txt:664` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **lawgroup_election_system**: добавлено вставкой
- **lawgroup_legislative_process**: добавлено вставкой
- **lawgroup_economic_incentives_public**: добавлено вставкой
- **lawgroup_working_hours**: добавлено вставкой
- **lawgroup_environment**: добавлено вставкой
- **lawgroup_centralization**: добавлено вставкой

## Поля

- **lawgroup_election_system**:
  - [[tgr/Законы/No Elections|No Elections]] = `disapprove`
  - [[tgr/Законы/Proportional System|Proportional System]] = `approve`
  - [[tgr/Законы/Majoritarian System|Majoritarian System]] = `neutral`
  - [[tgr/Законы/Mixed System|Mixed System]] = `neutral`
  - [[tgr/Законы/Ranked System|Ranked System]] = `strongly_approve`
- **lawgroup_legislative_process**:
  - [[tgr/Законы/Advisory Parliament Only|Advisory Parliament Only]] = `neutral`
  - [[tgr/Законы/Restricted Parliamentary Authority|Restricted Parliamentary Authority]] = `disapprove`
  - [[tgr/Законы/Balance of Powers|Balance of Powers]] = `neutral`
  - [[tgr/Законы/Unicameral Parliamentary System|Unicameral Parliamentary System]] = `approve`
  - [[tgr/Законы/Bicameral Parliamentary System|Bicameral Parliamentary System]] = `approve`
- **lawgroup_economic_incentives_public**:
  - [[tgr/Законы/No Incentive Focus (economic_incentives_no_focus_public)|No Incentive Focus (economic_incentives_no_focus_public)]] = `neutral`
  - [[tgr/Законы/Services Investments|Services Investments]] = `approve`
  - [[tgr/Законы/Public Sector Investments|Public Sector Investments]] = `strongly_approve`
  - [[tgr/Законы/Military Sector Investments|Military Sector Investments]] = `disapprove`
- **lawgroup_working_hours**:
  - [[tgr/Законы/Unregulated Working Hours|Unregulated Working Hours]] = `disapprove`
  - [[tgr/Законы/12-hour Work Days|12-hour Work Days]] = `neutral`
  - [[tgr/Законы/10-hour Work Days|10-hour Work Days]] = `approve`
  - [[tgr/Законы/8-hour Work Days|8-hour Work Days]] = `neutral`
- **lawgroup_environment**:
  - [[tgr/Законы/No Pollution Regulations|No Pollution Regulations]] = `disapprove`
  - [[tgr/Законы/Minimal Pollution Regulations|Minimal Pollution Regulations]] = `neutral`
  - [[tgr/Законы/Standard Pollution Regulations|Standard Pollution Regulations]] = `approve`
- **lawgroup_centralization**:
  - [[tgr/Законы/Administrative Decentralization|Administrative Decentralization]] = `strongly_approve`
  - [[tgr/Законы/Local Autonomies|Local Autonomies]] = `approve`
  - [[tgr/Законы/Administrative Centralization|Administrative Centralization]] = `neutral`
  - [[tgr/Законы/Economic Centralization|Economic Centralization]] = `disapprove`

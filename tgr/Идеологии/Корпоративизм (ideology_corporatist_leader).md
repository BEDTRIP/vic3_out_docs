---
type: concept
description: "Идеология «Корпоративизм (ideology_corporatist_leader)» — TGR 1.15, `ideology_corporatist_leader`"
project: vic3
audience: agent
source: tgr
aliases: ["Корпоративизм (ideology_corporatist_leader)", "Corporatist", "ideology_corporatist_leader"]
tags: [TGR, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_corporatist_leader
paths: [TheGreatRevision/common/ideologies/TGR_POLITICS_character_ideologies.txt]
replaces: "[[vanilla/Идеологии/Корпоративизм (ideology_corporatist_leader)]]"
---
# Корпоративизм (ideology_corporatist_leader)

Идеология · `ideology_corporatist_leader` · `common/ideologies/TGR_POLITICS_character_ideologies.txt:713` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **lawgroup_election_system**: добавлено вставкой
- **lawgroup_legislative_process**: добавлено вставкой
- **lawgroup_working_hours**: добавлено вставкой
- **lawgroup_social_security**: добавлено вставкой
- **lawgroup_retirement_age**: добавлено вставкой
- **lawgroup_salary_regulation**: добавлено вставкой

## Поля

- **lawgroup_election_system**:
  - [[tgr/Законы/No Elections|No Elections]] = `disapprove`
  - [[tgr/Законы/Proportional System|Proportional System]] = `neutral`
  - [[tgr/Законы/Majoritarian System|Majoritarian System]] = `neutral`
  - [[tgr/Законы/Mixed System|Mixed System]] = `approve`
  - [[tgr/Законы/Ranked System|Ranked System]] = `strongly_approve`
- **lawgroup_legislative_process**:
  - [[tgr/Законы/Advisory Parliament Only|Advisory Parliament Only]] = `disapprove`
  - [[tgr/Законы/Restricted Parliamentary Authority|Restricted Parliamentary Authority]] = `disapprove`
  - [[tgr/Законы/Balance of Powers|Balance of Powers]] = `neutral`
  - [[tgr/Законы/Unicameral Parliamentary System|Unicameral Parliamentary System]] = `strongly_approve`
  - [[tgr/Законы/Bicameral Parliamentary System|Bicameral Parliamentary System]] = `neutral`
- **lawgroup_working_hours**:
  - [[tgr/Законы/Unregulated Working Hours|Unregulated Working Hours]] = `disapprove`
  - [[tgr/Законы/12-hour Work Days|12-hour Work Days]] = `approve`
  - [[tgr/Законы/10-hour Work Days|10-hour Work Days]] = `approve`
  - [[tgr/Законы/8-hour Work Days|8-hour Work Days]] = `neutral`
- **lawgroup_social_security**:
  - [[tgr/Законы/No Pension Payments|No Pension Payments]] = `disapprove`
  - [[tgr/Законы/Old Age Pension|Old Age Pension]] = `approve`
  - [[tgr/Законы/Social Security Payments|Social Security Payments]] = `approve`
  - [[tgr/Законы/National Institute of Social Security|National Institute of Social Security]] = `neutral`
- **lawgroup_retirement_age**:
  - [[tgr/Законы/No Retirement Age|No Retirement Age]] = `disapprove`
  - [[tgr/Законы/Inability to work|Inability to work]] = `approve`
  - [[tgr/Законы/Retirement after Contribution|Retirement after Contribution]] = `approve`
  - [[tgr/Законы/Standar Retirement Age|Standar Retirement Age]] = `neutral`
- **lawgroup_salary_regulation**:
  - [[tgr/Законы/No Salary Regulations|No Salary Regulations]] = `disapprove`
  - [[tgr/Законы/Pro-Business Regulations|Pro-Business Regulations]] = `disapprove`
  - [[tgr/Законы/Standard Salary Regulations|Standard Salary Regulations]] = `approve`
  - [[tgr/Законы/Pro-Workers Regulations|Pro-Workers Regulations]] = `neutral`

---
type: concept
description: "Идеология «Земельный реформатор (ideology_land_reformer)» — TGR 1.13, `ideology_land_reformer`"
project: vic3
source: tgr
aliases: ["Земельный реформатор (ideology_land_reformer)", "Land Reformer", "ideology_land_reformer"]
tags: [TGR, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_land_reformer
paths: [TheGreatRevision/common/ideologies/TGR_POLITICS_character_ideologies.txt]
replaces: "[[vanilla/Идеологии/Земельный реформатор (ideology_land_reformer)]]"
---
# Земельный реформатор (ideology_land_reformer)

Идеология · `ideology_land_reformer` · `common/ideologies/TGR_POLITICS_character_ideologies.txt:611` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **lawgroup_environment**: добавлено вставкой
- **lawgroup_colonization**: добавлено вставкой
- **lawgroup_economic_incentives_primary**: добавлено вставкой

## Поля

- **lawgroup_environment**:
  - [[tgr/Законы/No Pollution Regulations|No Pollution Regulations]] = `disapprove`
  - [[tgr/Законы/Minimal Pollution Regulations|Minimal Pollution Regulations]] = `neutral`
  - [[tgr/Законы/Standard Pollution Regulations|Standard Pollution Regulations]] = `approve`
  - [[tgr/Законы/Eco-Friendly Pollution Regulations|Eco-Friendly Pollution Regulations]] = `strongly_approve`
- **lawgroup_colonization**:
  - [[tgr/Законы/Нет колоний|Нет колоний]] = `neutral`
  - [[tgr/Законы/Переселение в колонии|Переселение в колонии]] = `neutral`
  - [[tgr/Законы/Колониальная эксплуатация|Колониальная эксплуатация]] = `disapprove`
  - [[tgr/Законы/Колонизация границ|Колонизация границ]] = `strongly_approve`
- **lawgroup_economic_incentives_primary**:
  - [[tgr/Законы/No Incentive Focus (economic_incentives_no_focus_primary)|No Incentive Focus (economic_incentives_no_focus_primary)]] = `disapprove`
  - [[tgr/Законы/Agricultural Investments|Agricultural Investments]] = `strongly_approve`
  - [[tgr/Законы/Plantation Investments|Plantation Investments]] = `approve`
  - [[tgr/Законы/Fishing Investments|Fishing Investments]] = `neutral`

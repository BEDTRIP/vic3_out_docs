---
type: concept
description: "Идеология «Этнонационализм (ideology_ethno_nationalist)» — TGR 1.15, `ideology_ethno_nationalist`"
project: vic3
audience: agent
source: tgr
aliases: ["Этнонационализм (ideology_ethno_nationalist)", "Ethno-Nationalist", "ideology_ethno_nationalist"]
tags: [TGR, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_ethno_nationalist
paths: [TheGreatRevision/common/ideologies/TGR_POLITICS_character_ideologies.txt]
replaces: "[[vanilla/Идеологии/Этнонационализм (ideology_ethno_nationalist)]]"
---
# Этнонационализм (ideology_ethno_nationalist)

Идеология · `ideology_ethno_nationalist` · `common/ideologies/TGR_POLITICS_character_ideologies.txt:405` · дополняет запись ваниль (`INJECT:`)

## Отличия от ваниль

- **lawgroup_church_and_state**: добавлено вставкой
- **lawgroup_internal_security**: добавлено вставкой
- **lawgroup_policing**: добавлено вставкой

## Поля

- **lawgroup_church_and_state**:
  - [[tgr/Законы/Государственная религия (закон)|Государственная религия (закон)]] = `approve`
  - [[tgr/Законы/Свобода совести|Свобода совести]] = `approve`
  - [[tgr/Законы/Полное разделение|Полное разделение]] = `disapprove`
  - [[tgr/Законы/Государственный атеизм|Государственный атеизм]] = `neutral`
- **lawgroup_internal_security**:
  - [[tgr/Законы/Гарантия свобод|Гарантия свобод]] = `approve`
  - [[tgr/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `disapprove`
  - [[tgr/Законы/Национальная гвардия|Национальная гвардия]] = `approve`
  - [[tgr/Законы/Тайная полиция|Тайная полиция]] = `neutral`
- **lawgroup_policing**:
  - [[tgr/Законы/Нет полиции|Нет полиции]] = `disapprove`
  - [[tgr/Законы/Местная полиция|Местная полиция]] = `neutral`
  - [[tgr/Законы/Профессиональная полиция|Профессиональная полиция]] = `approve`
  - [[tgr/Законы/Военизированная полиция|Военизированная полиция]] = `neutral`

---
type: concept
description: "Идеология «Либерализм (ideology_liberal_modern)» — ваниль 1.13, `ideology_liberal_modern`"
project: vic3
source: vanilla
aliases: ["Либерализм (ideology_liberal_modern)", "Liberal", "ideology_liberal_modern"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_liberal_modern
paths: [.vanillaVIC3/common/ideologies/00_ig_ideologies_event.txt]
---
# Либерализм (ideology_liberal_modern)

Идеология · `ideology_liberal_modern` · `common/ideologies/00_ig_ideologies_event.txt:64`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/liberal.dds`
- **priority**: `100`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Мультикультурализм|Мультикультурализм]] = `strongly_disapprove`
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `neutral`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `approve`
  - [[vanilla/Законы/Подданство|Подданство]] = `strongly_disapprove`
- **lawgroup_policing**:
  - [[vanilla/Законы/Нет полиции|Нет полиции]] = `neutral`
  - [[vanilla/Законы/Профессиональная полиция|Профессиональная полиция]] = `neutral`
  - [[vanilla/Законы/Местная полиция|Местная полиция]] = `disapprove`
  - [[vanilla/Законы/Военизированная полиция|Военизированная полиция]] = `strongly_disapprove`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Гарантия свобод|Гарантия свобод]] = `approve`
  - [[vanilla/Законы/Национальная гвардия|Национальная гвардия]] = `neutral`
  - [[vanilla/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `neutral`
  - [[vanilla/Законы/Тайная полиция|Тайная полиция]] = `strongly_disapprove`
- **lawgroup_free_speech**:
  - [[vanilla/Законы/Защита свободы слова|Защита свободы слова]] = `strongly_approve`
  - [[vanilla/Законы/Право собрания|Право собрания]] = `approve`
  - [[vanilla/Законы/Цензура|Цензура]] = `neutral`
  - [[vanilla/Законы/Запрет на критику|Запрет на критику]] = `disapprove`
- **lawgroup_rights_of_women**:
  - [[vanilla/Законы/Попечительство|Попечительство]] = `disapprove`
  - [[vanilla/Законы/Право собственности для женщин|Право собственности для женщин]] = `approve`
  - [[vanilla/Законы/Женщины на рабочем месте|Женщины на рабочем месте]] = `approve`
  - [[vanilla/Законы/Женское избирательное право|Женское избирательное право]] = `approve`

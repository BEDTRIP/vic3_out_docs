---
type: concept
description: "Идеология «Subsidiary State» — BPM 1.13, `ideology_sta_regionalized_state`"
project: vic3
source: bpm
aliases: ["Subsidiary State", "ideology_sta_regionalized_state"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_sta_regionalized_state
paths: [BPM/common/ideologies/bpm_sta_ig_ideologies.txt]
---
# Subsidiary State

Идеология · `ideology_sta_regionalized_state` · `common/ideologies/bpm_sta_ig_ideologies.txt:567`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/sta_ideology/subsidary_state.dds`
- **priority**: `1000`
- **lawgroup_centralization**:
  - [[bpm/Законы/Унитарное|Унитарное]] = `disapprove`
  - [[bpm/Законы/Децентрализованное|Децентрализованное]] = `neutral`
  - [[bpm/Законы/Федеративное|Федеративное]] = `approve`
  - [[bpm/Законы/Конфедеративное|Конфедеративное]] = `strongly_approve`
  - [[bpm/Законы/Лоскутное управление|Лоскутное управление]] = `disapprove`
- **lawgroup_internal_security**:
  - [[vanilla/Законы/Отсутствие внутренних дел|Отсутствие внутренних дел]] = `approve`
  - [[bpm/Законы/Национальная гвардия|Национальная гвардия]] = `neutral`
  - [[bpm/Законы/Тайная полиция|Тайная полиция]] = `disapprove`
  - [[bpm/Законы/Гарантия свобод|Гарантия свобод]] = `approve`
- **lawgroup_policing**:
  - [[bpm/Законы/Отсутствие формальной полиции|Отсутствие формальной полиции]] = `disapprove`
  - [[bpm/Законы/Только местная полиция|Только местная полиция]] = `approve`
  - [[bpm/Законы/Национальная полиция|Национальная полиция]] = `neutral`
  - [[bpm/Законы/Милитаризованная полиция|Милитаризованная полиция]] = `strongly_disapprove`
  - [[bpm/Законы/Выборная полиция|Выборная полиция]] = `disapprove`
- **lawgroup_free_speech**:
  - [[bpm/Законы/Запрет на критику|Запрет на критику]] = `strongly_disapprove`
  - [[bpm/Законы/Цензура|Цензура]] = `disapprove`
  - [[bpm/Законы/Государственные СМИ|Государственные СМИ]] = `strongly_approve`
  - [[bpm/Законы/Без вмешательства в речь|Без вмешательства в речь]] = `approve`
- **lawgroup_repeatable_politics**:
  - [[bpm/Законы/Чистка в армии|Чистка в армии]] = `disapprove`
  - [[bpm/Законы/Бюрократическая чистка|Бюрократическая чистка]] = `disapprove`
  - [[bpm/Законы/Незначительные уступки|Незначительные уступки]] = `approve`
  - [[bpm/Законы/Кампания по борьбе с коррупцией|Кампания по борьбе с коррупцией]] = `approve`
  - [[bpm/Законы/law_repeatable_politics_great_terror|law_repeatable_politics_great_terror]] = `strongly_disapprove`

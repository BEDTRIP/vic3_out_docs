---
type: concept
description: "Идеология «Суверенизм (ideology_sovereignist_leader)» — BPM 1.13, `ideology_sovereignist_leader`"
project: vic3
audience: agent
source: bpm
aliases: ["Суверенизм (ideology_sovereignist_leader)", "Sovereignist", "ideology_sovereignist_leader"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_sovereignist_leader
paths: [BPM/common/ideologies/bpm_leader_ideologies.txt]
replaces: "[[vanilla/Идеологии/Суверенизм (ideology_sovereignist_leader)]]"
---
# Суверенизм (ideology_sovereignist_leader)

Идеология · `ideology_sovereignist_leader` · `common/ideologies/bpm_leader_ideologies.txt:9141` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **show_in_list**: добавлено
- **lawgroup_citizenship**: изменено
- **lawgroup_repeatable_politics**: добавлено
- **lawgroup_repeatable_culture**: добавлено
- **country_trigger**: изменено
- **interest_group_leader_trigger**: изменено
- **non_interest_group_leader_trigger**: изменено
- **interest_group_leader_weight**: изменено
- **non_interest_group_leader_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_sovereignist.dds`
- **character_ideology**: `yes`
- **show_in_list**: `yes`
- **lawgroup_policing**:
  - [[bpm/Законы/Только местная полиция|Только местная полиция]] = `approve`
  - [[bpm/Законы/Отсутствие формальной полиции|Отсутствие формальной полиции]] = `neutral`
  - [[bpm/Законы/Национальная полиция|Национальная полиция]] = `disapprove`
  - [[bpm/Законы/Милитаризованная полиция|Милитаризованная полиция]] = `strongly_disapprove`
- **lawgroup_migration**:
  - [[vanilla/Законы/Закрытые границы|Закрытые границы]] = `approve`
  - [[vanilla/Законы/Миграционный контроль|Миграционный контроль]] = `strongly_approve`
  - [[vanilla/Законы/Миграция не контролируется|Миграция не контролируется]] = `disapprove`
- **lawgroup_free_speech**:
  - [[bpm/Законы/Запрет на критику|Запрет на критику]] = `strongly_disapprove`
  - [[bpm/Законы/Цензура|Цензура]] = `disapprove`
  - [[bpm/Законы/Государственные СМИ|Государственные СМИ]] = `approve`
  - [[bpm/Законы/Без вмешательства в речь|Без вмешательства в речь]] = `strongly_approve`
- **lawgroup_citizenship**:
  - [[vanilla/Законы/Этническое государство|Этническое государство]] = `strongly_disapprove`
  - [[vanilla/Законы/Национальное превосходство|Национальное превосходство]] = `disapprove`
  - [[vanilla/Законы/Расовая сегрегация|Расовая сегрегация]] = `disapprove`
  - [[vanilla/Законы/Культурное отчуждение|Культурное отчуждение]] = `neutral`
  - [[bpm/Законы/Космополитизм|Космополитизм]] = `approve`
- **lawgroup_repeatable_politics**:
  - [[bpm/Законы/Чистка в армии|Чистка в армии]] = `disapprove`
  - [[bpm/Законы/Бюрократическая чистка|Бюрократическая чистка]] = `disapprove`
  - [[bpm/Законы/Незначительные уступки|Незначительные уступки]] = `approve`
  - [[bpm/Законы/Кампания по борьбе с коррупцией|Кампания по борьбе с коррупцией]] = `approve`
  - [[bpm/Законы/law_repeatable_politics_great_terror|law_repeatable_politics_great_terror]] = `strongly_disapprove`
- **lawgroup_repeatable_culture**:
  - [[bpm/Законы/Пригласить иностранных специалистов|Пригласить иностранных специалистов]] = `neutral`
  - [[bpm/Законы/Продвижение демократических ценностей|Продвижение демократических ценностей]] = `approve`
  - [[bpm/Законы/law_repeatable_culture_affirmative_action|law_repeatable_culture_affirmative_action]] = `strongly_approve`
  - [[bpm/Законы/Продвижение социалистических ценностей|Продвижение социалистических ценностей]] = `neutral`
  - [[bpm/Законы/Продвижение патриотических ценностей|Продвижение патриотических ценностей]] = `neutral`
  - [[bpm/Законы/Продвижение абсолютистских ценностей|Продвижение абсолютистских ценностей]] = `strongly_disapprove`
  - [[bpm/Законы/Продвижение ультранационалистических ценностей|Продвижение ультранационалистических ценностей]] = `strongly_disapprove`
- **country_trigger**:
  - `is_country_type` = `colonial`
- **interest_group_leader_trigger**: скрипт, строки 9197–9201
- **non_interest_group_leader_trigger**: скрипт, строки 9203–9212
- **interest_group_leader_weight**:
  - `value` = `100`
- **non_interest_group_leader_weight**:
  - `value` = `100`

## Ссылаются

- **Группы интересов** (character_ideologies): [[bpm/Группы интересов/Christian Democrats|Christian Democrats]], [[bpm/Группы интересов/Консерваторы|Консерваторы]], [[bpm/Группы интересов/Национал-либералы|Национал-либералы]], [[bpm/Группы интересов/Профессиональные интересы|Профессиональные интересы]]

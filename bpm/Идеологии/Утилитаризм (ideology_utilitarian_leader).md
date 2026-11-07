---
type: concept
description: "Идеология «Утилитаризм (ideology_utilitarian_leader)» — BPM 1.13, `ideology_utilitarian_leader`"
project: vic3
source: bpm
aliases: ["Утилитаризм (ideology_utilitarian_leader)", "Utilitarian", "ideology_utilitarian_leader"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_utilitarian_leader
paths: [BPM/common/ideologies/bpm_leader_ideologies.txt]
replaces: "[[vanilla/Идеологии/Утилитаризм (ideology_utilitarian_leader)]]"
---
# Утилитаризм (ideology_utilitarian_leader)

Идеология · `ideology_utilitarian_leader` · `common/ideologies/bpm_leader_ideologies.txt:8964` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **show_in_list**: добавлено
- **lawgroup_slavery**: изменено
- **lawgroup_repeatable_economy**: добавлено
- **interest_group_leader_trigger**: изменено
- **non_interest_group_leader_trigger**: изменено
- **interest_group_leader_weight**: изменено
- **non_interest_group_leader_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_utilitarian.dds`
- **character_ideology**: `yes`
- **show_in_list**: `yes`
- **lawgroup_childrens_rights**:
  - [[vanilla/Законы/Обязательное начальное образование|Обязательное начальное образование]] = `strongly_approve`
  - [[vanilla/Законы/Ограниченный детский труд|Ограниченный детский труд]] = `neutral`
  - [[vanilla/Законы/Детский труд разрешён|Детский труд разрешён]] = `neutral`
- **lawgroup_education_system**:
  - [[bpm/Законы/Государственные школы|Государственные школы]] = `approve`
  - [[bpm/Законы/Частные школы|Частные школы]] = `neutral`
  - [[bpm/Законы/Религиозные школы|Религиозные школы]] = `neutral`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
- **lawgroup_rights_of_women**:
  - [[vanilla/Законы/Попечительство|Попечительство]] = `disapprove`
  - [[vanilla/Законы/Право собственности для женщин|Право собственности для женщин]] = `neutral`
  - [[vanilla/Законы/Женщины на рабочем месте|Женщины на рабочем месте]] = `approve`
  - [[bpm/Законы/Женское избирательное право|Женское избирательное право]] = `strongly_approve`
- **lawgroup_slavery**:
  - [[bpm/Законы/Запрет рабства|Запрет рабства]] = `neutral`
  - [[bpm/Законы/Долговое рабство|Долговое рабство]] = `strongly_disapprove`
  - [[bpm/Законы/Работорговля|Работорговля]] = `strongly_disapprove`
  - [[bpm/Законы/Унаследованное рабство|Унаследованное рабство]] = `disapprove`
  - [[vanilla/Законы/Колониальное рабство|Колониальное рабство]] = `disapprove`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `disapprove`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `neutral`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_approve`
  - [[bpm/Законы/Крестьянский налог|Крестьянский налог]] = `disapprove`
- **lawgroup_caste_hegemony**:
  - [[vanilla/Законы/Принудительная кастовая система|Принудительная кастовая система]] = `disapprove`
  - [[vanilla/Законы/Кодифицированная кастовая система|Кодифицированная кастовая система]] = `disapprove`
  - [[vanilla/Законы/Необязательная кастовая система|Необязательная кастовая система]] = `neutral`
  - [[vanilla/Законы/Позитивная дискриминация|Позитивная дискриминация]] = `neutral`
- **lawgroup_repeatable_economy**:
  - [[bpm/Законы/Экономическая либерализация|Экономическая либерализация]] = `approve`
  - [[bpm/Законы/Сельскохозяйственные инвестиции|Сельскохозяйственные инвестиции]] = `approve`
  - [[bpm/Законы/Крестьянская повинность|Крестьянская повинность]] = `strongly_disapprove`
  - [[bpm/Законы/Общественные работы|Общественные работы]] = `approve`
  - [[bpm/Законы/Принудительная индустриализация|Принудительная индустриализация]] = `strongly_disapprove`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Эмпиризм|Эмпиризм]]
  - **any_primary_culture**:
    - `has_discrimination_trait` = `language_anglophone`
- **interest_group_leader_trigger**: скрипт, строки 9028–9048
- **non_interest_group_leader_trigger**: скрипт, строки 9050–9087
- **interest_group_leader_weight**: скрипт, строки 9089–9125
- **non_interest_group_leader_weight**: скрипт, строки 9127–9138

## Ссылаются

- **Группы интересов** (character_ideologies): [[bpm/Группы интересов/Рыночные либералы|Рыночные либералы]]

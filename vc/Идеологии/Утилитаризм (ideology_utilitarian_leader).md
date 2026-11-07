---
type: concept
description: "Идеология «Утилитаризм (ideology_utilitarian_leader)» — VC 1.13, `ideology_utilitarian_leader`"
project: vic3
source: vc
aliases: ["Утилитаризм (ideology_utilitarian_leader)", "Utilitarian", "ideology_utilitarian_leader"]
tags: [VC, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_utilitarian_leader
paths: [VC/common/ideologies/joi_leader_ideologies.txt]
replaces: "[[vanilla/Идеологии/Утилитаризм (ideology_utilitarian_leader)]]"
---
# Утилитаризм (ideology_utilitarian_leader)

Идеология · `ideology_utilitarian_leader` · `common/ideologies/joi_leader_ideologies.txt:1`

## Отличия от ваниль

- **lawgroup_slavery**: изменено
- **interest_group_leader_weight**: изменено
- **non_interest_group_leader_weight**: изменено

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_utilitarian.dds`
- **character_ideology**: `yes`
- **lawgroup_childrens_rights**:
  - [[vanilla/Законы/Обязательное начальное образование|Обязательное начальное образование]] = `strongly_approve`
  - [[vanilla/Законы/Ограниченный детский труд|Ограниченный детский труд]] = `neutral`
  - [[vanilla/Законы/Детский труд разрешён|Детский труд разрешён]] = `neutral`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `approve`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `neutral`
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `neutral`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
- **lawgroup_rights_of_women**:
  - [[vanilla/Законы/Попечительство|Попечительство]] = `disapprove`
  - [[vanilla/Законы/Право собственности для женщин|Право собственности для женщин]] = `neutral`
  - [[vanilla/Законы/Женщины на рабочем месте|Женщины на рабочем месте]] = `approve`
  - [[vanilla/Законы/Женское избирательное право|Женское избирательное право]] = `strongly_approve`
- **lawgroup_slavery**:
  - [[vanilla/Законы/Запрет рабства|Запрет рабства]] = `approve`
  - [[vanilla/Законы/Долговое рабство|Долговое рабство]] = `strongly_disapprove`
  - [[vanilla/Законы/Работорговля|Работорговля]] = `strongly_disapprove`
  - [[vanilla/Законы/Унаследованное рабство|Унаследованное рабство]] = `disapprove`
  - [[vanilla/Законы/Колониальное рабство|Колониальное рабство]] = `neutral`
- **lawgroup_taxation**:
  - [[vanilla/Законы/Потребительское налогообложение|Потребительское налогообложение]] = `disapprove`
  - [[vanilla/Законы/Налог на душу населения|Налог на душу населения]] = `neutral`
  - [[vanilla/Законы/Пропорциональный налог|Пропорциональный налог]] = `approve`
  - [[vanilla/Законы/Прогрессивный налог|Прогрессивный налог]] = `strongly_approve`
  - [[vanilla/Законы/Земельное налогообложение|Земельное налогообложение]] = `disapprove`
- **lawgroup_caste_hegemony**:
  - [[vanilla/Законы/Принудительная кастовая система|Принудительная кастовая система]] = `disapprove`
  - [[vanilla/Законы/Кодифицированная кастовая система|Кодифицированная кастовая система]] = `disapprove`
  - [[vanilla/Законы/Необязательная кастовая система|Необязательная кастовая система]] = `neutral`
  - [[vanilla/Законы/Позитивная дискриминация|Позитивная дискриминация]] = `neutral`
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Эмпиризм|Эмпиризм]]
  - **any_primary_culture**:
    - `has_discrimination_trait` = `language_anglophone`
- **interest_group_leader_trigger**:
  - `ideology_utilitarian_leader_valid_trigger` = `yes`
- **non_interest_group_leader_trigger**: скрипт, строки 60–77
- **interest_group_leader_weight**: скрипт, строки 79–123
- **non_interest_group_leader_weight**: скрипт, строки 125–159

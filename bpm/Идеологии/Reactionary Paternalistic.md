---
type: concept
description: "Идеология «Reactionary Paternalistic» — BPM 1.13, `ideology_wel_reactionary_paternalistic`"
project: vic3
audience: agent
source: bpm
aliases: ["Reactionary Paternalistic", "ideology_wel_reactionary_paternalistic"]
tags: [BPM, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_wel_reactionary_paternalistic
paths: [BPM/common/ideologies/bpm_wel_ig_ideologies.txt]
---
# Reactionary Paternalistic

Идеология · `ideology_wel_reactionary_paternalistic` · `common/ideologies/bpm_wel_ig_ideologies.txt:408`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/wel_ideology/reactionary_paternalistic.dds`
- **priority**: `1000`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
  - [[bpm/Законы/Религиозные школы|Религиозные школы]] = `approve`
  - [[bpm/Законы/Частные школы|Частные школы]] = `approve`
  - [[bpm/Законы/Государственные школы|Государственные школы]] = `neutral`
- **lawgroup_health_system**:
  - [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]] = `disapprove`
  - [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]] = `approve`
  - [[bpm/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]] = `neutral`
  - [[vanilla/Законы/Государственное медицинское страхование|Государственное медицинское страхование]] = `disapprove`
- **lawgroup_labor_rights**:
  - [[bpm/Законы/Нет прав трудящихся|Нет прав трудящихся]] = `neutral`
  - [[bpm/Законы/Регулирующие органы|Регулирующие органы]] = `approve`
  - [[bpm/Законы/Защита прав рабочих|Защита прав рабочих]] = `strongly_disapprove`
- **lawgroup_childrens_rights**:
  - [[vanilla/Законы/Детский труд разрешён|Детский труд разрешён]] = `disapprove`
  - [[vanilla/Законы/Ограниченный детский труд|Ограниченный детский труд]] = `approve`
  - [[vanilla/Законы/Обязательное начальное образование|Обязательное начальное образование]] = `neutral`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `neutral`
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `disapprove`
- **lawgroup_work_time_regulations**:
  - [[bpm/Законы/Неурегулированное рабочее время|Неурегулированное рабочее время]] = `neutral`
  - [[bpm/Законы/Символическое регулирование рабочего времени|Символическое регулирование рабочего времени]] = `approve`
  - [[bpm/Законы/Ограниченное рабочее время|Ограниченное рабочее время]] = `disapprove`
  - [[bpm/Законы/Право на отдых|Право на отдых]] = `disapprove`

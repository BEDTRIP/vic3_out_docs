---
type: concept
description: "Идеология «Корпоративизм (ideology_corporatist)» — ваниль 1.13, `ideology_corporatist`"
project: vic3
audience: agent
source: vanilla
aliases: ["Корпоративизм (ideology_corporatist)", "Corporatist", "ideology_corporatist"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_corporatist
paths: [.vanillaVIC3/common/ideologies/00_ig_ideologies.txt]
---
# Корпоративизм (ideology_corporatist)

Идеология · `ideology_corporatist` · `common/ideologies/00_ig_ideologies.txt:944`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/corporatist.dds`
- **lawgroup_health_system**:
  - [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]] = `approve`
  - [[vanilla/Законы/Государственное медицинское страхование|Государственное медицинское страхование]] = `neutral`
  - [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]] = `disapprove`
  - [[vanilla/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]] = `disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `approve`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `neutral`
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `disapprove`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `disapprove`
- **lawgroup_labor_rights**:
  - [[vanilla/Законы/Нет прав трудящихся|Нет прав трудящихся]] = `neutral`
  - [[vanilla/Законы/Регулирующие органы|Регулирующие органы]] = `approve`
  - [[vanilla/Законы/Защита прав рабочих|Защита прав рабочих]] = `neutral`
- **lawgroup_welfare**:
  - [[vanilla/Законы/Законы о бедняках|Законы о бедняках]] = `neutral`
  - [[vanilla/Законы/Нет социальной защиты|Нет социальной защиты]] = `disapprove`
  - [[vanilla/Законы/Субсидирование зарплат|Субсидирование зарплат]] = `approve`
  - [[vanilla/Законы/Пенсия по старости|Пенсия по старости]] = `neutral`
- **lawgroup_labour_associations**:
  - [[vanilla/Законы/Законы о собраниях|Законы о собраниях]] = `neutral`
  - [[vanilla/Законы/Система гильдий|Система гильдий]] = `approve`
  - [[vanilla/Законы/Запрет забастовок|Запрет забастовок]] = `approve`
  - [[vanilla/Законы/Государственные профсоюзы|Государственные профсоюзы]] = `strongly_approve`
  - [[vanilla/Законы/Свобода объединения|Свобода объединения]] = `disapprove`
  - [[vanilla/Законы/Фабричный совет|Фабричный совет]] = `strongly_disapprove`

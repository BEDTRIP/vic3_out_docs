---
type: concept
description: "Идеология «Корпоративизм (ideology_corporatist_leader)» — ваниль 1.15, `ideology_corporatist_leader`"
project: vic3
audience: agent
source: vanilla
aliases: ["Корпоративизм (ideology_corporatist_leader)", "Corporatist", "ideology_corporatist_leader"]
tags: [ваниль, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_corporatist_leader
paths: [.vanillaVIC3/common/ideologies/01_character_ideologies.txt]
---
# Корпоративизм (ideology_corporatist_leader)

Идеология · `ideology_corporatist_leader` · `common/ideologies/01_character_ideologies.txt:10045`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_leader/ideology_leader_corporatist.dds`
- **character_ideology**: `yes`
- **lawgroup_governance_principles**:
  - [[vanilla/Законы/Теократия|Теократия]] = `neutral`
  - [[vanilla/Законы/Монархия|Монархия]] = `neutral`
  - [[vanilla/Законы/Президентская республика|Президентская республика]] = `neutral`
  - [[vanilla/Законы/Парламентская республика|Парламентская республика]] = `neutral`
  - [[vanilla/Законы/Корпоративное государство|Корпоративное государство]] = `approve`
  - [[vanilla/Законы/Социальная монархия|Социальная монархия]] = `approve`
  - [[vanilla/Законы/Советская республика|Советская республика]] = `strongly_disapprove`
- **lawgroup_education_system**:
  - [[vanilla/Законы/Государственные школы|Государственные школы]] = `approve`
  - [[vanilla/Законы/Религиозные школы|Религиозные школы]] = `approve`
  - [[vanilla/Законы/Частные школы|Частные школы]] = `neutral`
  - [[vanilla/Законы/Нет школ|Нет школ]] = `disapprove`
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
- **country_trigger**:
  - `has_technology_researched` = [[vanilla/Технологии/Корпоративизм|Корпоративизм]]
- **non_interest_group_leader_trigger**: скрипт, строки 10093–10106
- **interest_group_leader_weight**: скрипт, строки 10108–10245
- **non_interest_group_leader_weight**: скрипт, строки 10247–10354

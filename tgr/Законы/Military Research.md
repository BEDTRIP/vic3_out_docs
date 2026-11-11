---
type: concept
description: "Закон «Military Research» — TGR 1.15, `law_tgr_research_military`"
project: vic3
audience: agent
source: tgr
aliases: ["Military Research", "law_tgr_research_military"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_tgr_research_military
paths: [TheGreatRevision/common/laws/TGR_POLITICS_research_focus.txt]
---
# Military Research

Закон · `law_tgr_research_military` · `common/laws/TGR_POLITICS_research_focus.txt:35`

## Поля

- **group**: [[tgr/Группы законов/Technological Research|Technological Research]]
- **icon**: `gfx/interface/icons/law_icons/professional_army.dds`
- **progressiveness**: `0`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-research-speed-mult|country_production_tech_research_speed_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-military-tech-research-speed-mult|country_military_tech_research_speed_mult]] = `0.50`
  - [[vanilla/движок/Модификаторы C#^m-country-society-tech-research-speed-mult|country_society_tech_research_speed_mult]] = `-0.25`
- **on_enact**: скрипт, строки 44–44
- **on_activate**: скрипт, строки 45–47
- **on_deactivate**: скрипт, строки 48–48
- **ai_enact_weight_modifier**: скрипт, строки 49–55

## Ссылаются

- **Идеологии** (lawgroup_tgr_research_focus: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Государственный социализм|Государственный социализм]], [[tgr/Идеологии/Позитивист (ideology_positivist)|Позитивист (ideology_positivist)]], [[tgr/Идеологии/Протекционист|Протекционист]], [[tgr/Идеологии/Радикализм (ideology_radical)|Радикализм (ideology_radical)]], [[tgr/Идеологии/Реформы|Реформы]]
- **Идеологии** (lawgroup_tgr_research_focus: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Джингоизм|Джингоизм]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]]
- **Идеологии** (lawgroup_tgr_research_focus: strongly_disapprove): [[tgr/Идеологии/Пацифизм|Пацифизм]]

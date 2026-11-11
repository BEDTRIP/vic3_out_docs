---
type: concept
description: "Закон «Society Research» — TGR 1.15, `law_tgr_research_society`"
project: vic3
audience: agent
source: tgr
aliases: ["Society Research", "law_tgr_research_society"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_tgr_research_society
paths: [TheGreatRevision/common/laws/TGR_POLITICS_research_focus.txt]
---
# Society Research

Закон · `law_tgr_research_society` · `common/laws/TGR_POLITICS_research_focus.txt:58`

## Поля

- **group**: [[tgr/Группы законов/Technological Research|Technological Research]]
- **icon**: `gfx/interface/icons/law_icons/public_schools.dds`
- **progressiveness**: `0`
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-production-tech-research-speed-mult|country_production_tech_research_speed_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-military-tech-research-speed-mult|country_military_tech_research_speed_mult]] = `-0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-society-tech-research-speed-mult|country_society_tech_research_speed_mult]] = `0.50`
- **on_enact**: скрипт, строки 67–67
- **on_activate**: скрипт, строки 68–70
- **on_deactivate**: скрипт, строки 71–71
- **ai_enact_weight_modifier**: скрипт, строки 72–77

## Ссылаются

- **Идеологии** (lawgroup_tgr_research_focus: approve): [[tgr/Идеологии/Пацифизм|Пацифизм]]
- **Идеологии** (lawgroup_tgr_research_focus: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_armed_forces)|Government Policies (ideology_government_armed_forces)]], [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]], [[tgr/Идеологии/Джингоизм|Джингоизм]], [[tgr/Идеологии/Позитивист (ideology_positivist)|Позитивист (ideology_positivist)]], [[tgr/Идеологии/Протекционист|Протекционист]], [[tgr/Идеологии/Фашизм (ideology_fascist)|Фашизм (ideology_fascist)]]
- **Идеологии** (lawgroup_tgr_research_focus: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Государственный социализм|Государственный социализм]], [[tgr/Идеологии/Радикализм (ideology_radical)|Радикализм (ideology_radical)]], [[tgr/Идеологии/Реформы|Реформы]]

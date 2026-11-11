---
type: concept
description: "Закон «No Pollution Regulations» — TGR 1.15, `law_no_environment_regulations`"
project: vic3
audience: agent
source: tgr
aliases: ["No Pollution Regulations", "law_no_environment_regulations"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_no_environment_regulations
paths: [TheGreatRevision/common/laws/TGR_POLITICS_environment_regulations.txt]
---
# No Pollution Regulations

Закон · `law_no_environment_regulations` · `common/laws/TGR_POLITICS_environment_regulations.txt:1`

## Поля

- **group**: [[tgr/Группы законов/Pollution Regulations|Pollution Regulations]]
- **icon**: `gfx/interface/icons/law_icons/industry_banned.dds`
- **progressiveness**: `50`
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `0.2`
- **ai_will_do**: скрипт, строки 12–14
- **ai_enact_weight_modifier**: скрипт, строки 16–23

## Ссылаются

- **Идеологии** (lawgroup_environment: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_intelligentsia)|Government Policies (ideology_government_intelligentsia)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer)|Земельный реформатор (ideology_land_reformer)]], [[tgr/Идеологии/Земельный реформатор (ideology_land_reformer_movement)|Земельный реформатор (ideology_land_reformer_movement)]], [[tgr/Идеологии/Либерализм (ideology_liberal_movement)|Либерализм (ideology_liberal_movement)]]
- **Идеологии** (lawgroup_environment: strongly_approve): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]
- **Идеологии** (lawgroup_environment: strongly_disapprove): [[tgr/Идеологии/Government Policies (ideology_government_rural_folk)|Government Policies (ideology_government_rural_folk)]], [[tgr/Идеологии/Луддит|Луддит]]

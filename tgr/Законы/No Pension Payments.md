---
type: concept
description: "Закон «No Pension Payments» — TGR 1.15, `law_no_pension`"
project: vic3
audience: agent
source: tgr
aliases: ["No Pension Payments", "law_no_pension"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_no_pension
paths: [TheGreatRevision/common/laws/TGR_POLITICS_pension.txt]
---
# No Pension Payments

Закон · `law_no_pension` · `common/laws/TGR_POLITICS_pension.txt:1`

## Поля

- **group**: [[tgr/Группы законов/Social Security|Social Security]]
- **icon**: `gfx/interface/icons/law_icons/no_social_security.dds`
- **progressiveness**: `0`
- **ai_will_do**: скрипт, строки 9–11
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-mass-migration-attraction-mult|country_mass_migration_attraction_mult]] = `-0.05`
- **ai_enact_weight_modifier**: скрипт, строки 17–24

## Ссылаются

- **Идеологии** (lawgroup_social_security: approve): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
- **Идеологии** (lawgroup_social_security: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Пролетарство|Пролетарство]], [[tgr/Идеологии/Социалисты|Социалисты]]
- **Идеологии** (lawgroup_social_security: neutral): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]

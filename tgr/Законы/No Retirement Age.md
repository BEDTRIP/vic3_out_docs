---
type: concept
description: "Закон «No Retirement Age» — TGR 1.13, `law_no_retirement_age`"
project: vic3
source: tgr
aliases: ["No Retirement Age", "law_no_retirement_age"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_no_retirement_age
paths: [TheGreatRevision/common/laws/TGR_POLITICS_retirement_age.txt]
---
# No Retirement Age

Закон · `law_no_retirement_age` · `common/laws/TGR_POLITICS_retirement_age.txt:1`

## Поля

- **group**: [[tgr/Группы законов/Retirement Age Policy|Retirement Age Policy]]
- **icon**: `gfx/interface/icons/law_icons/no_social_security.dds`
- **progressiveness**: `0`
- **ai_will_do**: скрипт, строки 9–11
- **modifier**:
  - `state_radicals_and_loyalists_from_sol_change_mult` = `0.25`
  - `country_mass_migration_attraction_mult` = `-0.05`
- **ai_enact_weight_modifier**: скрипт, строки 18–25
- **on_activate**: скрипт, строки 27–49

## Ссылаются

- **Законы** (запрещает закон): [[tgr/Законы/National Institute of Social Security|National Institute of Social Security]], [[tgr/Законы/Old Age Pension|Old Age Pension]], [[tgr/Законы/Social Security Payments|Social Security Payments]]
- **Идеологии** (lawgroup_retirement_age: approve): [[tgr/Идеологии/Government Policies (ideology_government_landowners)|Government Policies (ideology_government_landowners)]]
- **Идеологии** (lawgroup_retirement_age: disapprove): [[tgr/Идеологии/Government Policies (ideology_government_devout)|Government Policies (ideology_government_devout)]], [[tgr/Идеологии/Government Policies (ideology_government_trade_unions)|Government Policies (ideology_government_trade_unions)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_leader)|Корпоративизм (ideology_corporatist_leader)]], [[tgr/Идеологии/Корпоративизм (ideology_corporatist_movement)|Корпоративизм (ideology_corporatist_movement)]], [[tgr/Идеологии/Пролетарии|Пролетарии]], [[tgr/Идеологии/Социалисты|Социалисты]], [[tgr/Идеологии/Социальная демократия|Социальная демократия]]
- **Идеологии** (lawgroup_retirement_age: neutral): [[tgr/Идеологии/Government Policies (ideology_government_industrialist)|Government Policies (ideology_government_industrialist)]]

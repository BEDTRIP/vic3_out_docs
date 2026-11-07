---
type: concept
description: "Закон «Provincial Autonomy» — Mandate of Heaven 1.13, `law_provincial_autonomy`"
project: vic3
source: mandate_of_heaven
aliases: ["Provincial Autonomy", "law_provincial_autonomy"]
tags: [mandate_of_heaven, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_provincial_autonomy
paths: [for addon/Mandate of Heaven/common/laws/moh_flavoured_laws.txt]
---
# Provincial Autonomy

Закон · `law_provincial_autonomy` · `common/laws/moh_flavoured_laws.txt:127`

## Поля

- **group**: [[vanilla/Группы законов/Принципы управления|Принципы управления]]
- **parent**: [[vanilla/Законы/Президентская республика|Президентская республика]]
- **icon**: `gfx/interface/icons/law_icons/law_provincial_autonomy.dds`
- **progressiveness**: `100`
- **unlocking_technologies**: [[vanilla/Технологии/Демократия|Демократия]]
- **is_visible**: скрипт, строки 136–143
- **can_enact**: скрипт, строки 145–152
- **modifier**:
  - `country_legitimacy_headofstate_add` = `5`
  - `country_legitimacy_govt_total_votes_add` = `10`
  - `country_legitimacy_ideological_incoherence_mult` = `-0.15`
  - `country_authority_add` = `-10`
  - `country_construction_add` = `5`
- **ai_will_do**: скрипт, строки 162–176
- **ai_enact_weight_modifier**: скрипт, строки 178–188

---
type: concept
description: "Закон «Imperial Divan» — Gates of Bosphorus 1.13, `law_imperial_divan`"
project: vic3
source: gates_of_bosphorus
aliases: ["Imperial Divan", "law_imperial_divan"]
tags: [gates_of_bosphorus, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_imperial_divan
paths: [for addon/gatesofbosphorus/common/laws/gbbf_governance_principles.txt]
---
# Imperial Divan

Закон · `law_imperial_divan` · `common/laws/gbbf_governance_principles.txt:1`

## Поля

- **icon**: `gfx/interface/icons/law_icons/neo_absolutism.dds`
- **group**: [[vanilla/Группы законов/Распределение власти|Распределение власти]]
- **parent**: [[vanilla/Законы/Автократия|Автократия]]
- **progressiveness**: `-100`
- **is_visible**: скрипт, строки 7–12
- **disallowing_laws**: [[vanilla/Законы/Парламентская республика|Парламентская республика]]
- **can_impose**: скрипт, строки 18–20
- **on_activate**: скрипт, строки 22–26
- **modifier**:
  - `country_legitimacy_headofstate_add` = `30`
  - `country_legitimacy_govt_total_clout_add` = `120`
  - `country_legitimacy_ideological_incoherence_mult` = `0.25`
  - `country_aristocrats_pol_str_mult` = `0.25`
  - `country_bureaucrats_pol_str_mult` = `0.25`
  - `country_officers_pol_str_mult` = `0.25`
  - `country_authority_add` = `200`
- **on_deactivate**: скрипт, строки 38–49
- **ai_will_do**: скрипт, строки 51–55
- **ai_enact_weight_modifier**: скрипт, строки 57–62
- **ai_impose_chance**: скрипт, строки 64–66

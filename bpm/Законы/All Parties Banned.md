---
type: concept
description: "Закон «All Parties Banned» — BPM 1.13, `law_no_parties_allowed`"
project: vic3
audience: agent
source: bpm
aliases: ["All Parties Banned", "law_no_parties_allowed"]
tags: [BPM, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_no_parties_allowed
paths: [BPM/common/laws/BPM_party_laws.txt]
---
# All Parties Banned

Закон · `law_no_parties_allowed` · `common/laws/BPM_party_laws.txt:400`

## Поля

- **group**: [[bpm/Группы законов/Законы о партиях|Законы о партиях]]
- **parent**: [[bpm/Законы/Единственная легальная партия|Единственная легальная партия]]
- **icon**: `gfx/interface/icons/law_icons/single_party.dds`
- **progressiveness**: `-250`
- **disallowing_laws**: [[bpm/Законы/Без вмешательства в речь|Без вмешательства в речь]]
- **is_visible**: скрипт, строки 412–414
- **can_enact**: скрипт, строки 416–418
- **modifier**:
  - `bpm_decorative_ban_everyone` = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-bureaucrats-pol-str-mult|country_bureaucrats_pol_str_mult]] = `0.33`
  - `interest_group_ig_reactionaries_pol_str_mult` = `0.66`
  - `country_rigidity_baseline_add` = `10`
  - [[vanilla/движок/Модификаторы C#^m-country-authority-mult|country_authority_mult]] = `0.1`
- **ai_enact_weight_modifier**: скрипт, строки 428–435

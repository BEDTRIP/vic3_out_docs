---
type: concept
description: "Закон «Full Secularism» — BPM 1.13, `law_total_separation_upgraded`"
project: vic3
source: bpm
aliases: ["Full Secularism", "law_total_separation_upgraded"]
tags: [BPM, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_total_separation_upgraded
paths: [BPM/common/laws/BPM_church_and_state.txt]
---
# Full Secularism

Закон · `law_total_separation_upgraded` · `common/laws/BPM_church_and_state.txt:51`

## Поля

- **group**: [[vanilla/Группы законов/Церковь и государство|Церковь и государство]]
- **parent**: [[bpm/Законы/Секуляризм|Секуляризм]]
- **icon**: `gfx/interface/icons/law_icons/total_separation.dds`
- **progressiveness**: `100`
- **unlocking_technologies**: [[vanilla/Технологии/Эмпиризм|Эмпиризм]]
- **disallowing_laws**: [[bpm/Законы/Теократия|Теократия]]
- **can_enact**: скрипт, строки 67–74
- **is_visible**: скрипт, строки 76–78
- **on_activate**: скрипт, строки 80–94
- **modifier**:
  - `state_pop_support_movement_religious_majority_mult` = `-0.5`
  - `state_pop_support_movement_religious_minority_mult` = `-0.25`
  - `state_conversion_mult` = `0.25`
  - `country_acceptance_state_religion_add` = `15`
  - `country_acceptance_shared_religious_trait_add` = `15`
  - `country_acceptance_shared_religious_trait_group_add` = `15`
  - `country_acceptance_no_shared_religious_trait_add` = `15`
  - `country_allow_conversion_violent_hostility_bool` = `yes`
  - `country_allow_conversion_cultural_erasure_bool` = `yes`
  - `country_allow_conversion_open_prejudice_bool` = `yes`
  - `country_allow_conversion_second_rate_citizen_bool` = `yes`
  - `country_allow_conversion_full_acceptance_bool` = `yes`
- **can_impose**: скрипт, строки 113–124
- **ai_enact_weight_modifier**: скрипт, строки 126–133

## Ссылаются

- **Законы** (открывает закон): [[bpm/Законы/Продвижение светских ценностей|Продвижение светских ценностей]]

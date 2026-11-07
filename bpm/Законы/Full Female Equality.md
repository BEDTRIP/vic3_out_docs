---
type: concept
description: "Закон «Full Female Equality» — BPM 1.13, `law_womens_suffrage_upgraded`"
project: vic3
source: bpm
aliases: ["Full Female Equality", "law_womens_suffrage_upgraded"]
tags: [BPM, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_womens_suffrage_upgraded
paths: [BPM/common/laws/BPM_rights_of_women.txt]
---
# Full Female Equality

Закон · `law_womens_suffrage_upgraded` · `common/laws/BPM_rights_of_women.txt:21`

## Поля

- **group**: [[vanilla/Группы законов/Права женщин|Права женщин]]
- **parent**: [[bpm/Законы/Женское избирательное право|Женское избирательное право]]
- **icon**: `gfx/interface/icons/law_icons/womens_suffrage.dds`
- **progressiveness**: `100`
- **is_visible**: скрипт, строки 29–31
- **unlocking_technologies**: [[bpm/Технологии/Феминизм|Феминизм]]
- **unlocking_laws**: [[bpm/Законы/Имущественный ценз|Имущественный ценз]], [[bpm/Законы/Голосуют землевладельцы|Голосуют землевладельцы]], [[bpm/Законы/Голосуют богатые|Голосуют богатые]], [[bpm/Законы/Всеобщее избирательное право|Всеобщее избирательное право]], [[bpm/Законы/Однопартийное государство|Однопартийное государство]], [[bpm/Законы/Анархия|Анархия]]
- **on_enact**: скрипт, строки 46–48
- **modifier**:
  - `state_working_adult_ratio_add` = `0.2`
  - `state_birth_rate_mult` = `-0.05`
  - `country_tech_research_speed_mult` = `0.25`
  - `country_institution_suffrage_max_investment_add` = `1`
- **institution**: `institution_suffrage`
- **institution_modifier**:
  - `state_dependent_political_participation_add` = `0.08`
- **ai_enact_weight_modifier**: скрипт, строки 62–69

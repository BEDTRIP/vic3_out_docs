---
type: concept
description: "Закон «Nominal Separation» — Hail Columbia 1.13, `law_usfp_nominal_separation`"
project: vic3
source: hail_columbia
aliases: ["Nominal Separation", "law_usfp_nominal_separation"]
tags: [hail_columbia, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_usfp_nominal_separation
paths: [for addon/Hail Columbia/common/laws/usfp_law_variants.txt]
---
# Nominal Separation

Закон · `law_usfp_nominal_separation` · `common/laws/usfp_law_variants.txt:39`

## Поля

- **group**: [[vanilla/Группы законов/Церковь и государство|Церковь и государство]]
- **parent**: [[hail_columbia/Законы/Свобода совести|Свобода совести]]
- **icon**: `gfx/interface/icons/law_icons/usfp_nominal_separation.dds`
- **progressiveness**: `0`
- **unlocking_technologies**: [[vanilla/Технологии/Рационализм|Рационализм]]
- **disallowing_laws**: [[vanilla/Законы/Теократия|Теократия]]
- **is_visible**: скрипт, строки 54–59
- **on_enact**: скрипт, строки 68–82
- **modifier**:
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-state-religion-add|country_acceptance_state_religion_add]] = `15`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-religious-trait-add|country_acceptance_shared_religious_trait_add]] = `10`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-shared-religious-trait-group-add|country_acceptance_shared_religious_trait_group_add]] = `5`
  - [[vanilla/движок/Модификаторы C#^m-country-acceptance-no-shared-religious-trait-add|country_acceptance_no_shared_religious_trait_add]] = `0`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-conversion-violent-hostility-bool|country_allow_conversion_violent_hostility_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-conversion-cultural-erasure-bool|country_allow_conversion_cultural_erasure_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-conversion-open-prejudice-bool|country_allow_conversion_open_prejudice_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-conversion-second-rate-citizen-bool|country_allow_conversion_second_rate_citizen_bool]] = `yes`
  - [[vanilla/движок/Модификаторы C#^m-country-allow-conversion-full-acceptance-bool|country_allow_conversion_full_acceptance_bool]] = `yes`
- **can_impose**: скрипт, строки 97–108
- **ai_enact_weight_modifier**: скрипт, строки 110–117

## Ссылаются

- **Методы производства** (запрещает закон): [[hail_columbia/Методы производства/Административное духовенство|Административное духовенство]], [[hail_columbia/Методы производства/Учителя-священники|Учителя-священники]]

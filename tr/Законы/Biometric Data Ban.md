---
type: concept
description: "Закон «Biometric Data Ban» — T&R 1.13, `law_data_biometric_ban`"
project: vic3
source: tr
aliases: ["Biometric Data Ban", "law_data_biometric_ban"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_data_biometric_ban
paths: [TechRes+Kuromi/t&r/common/laws/ztr_data_policy.txt]
---
# Biometric Data Ban

Закон · `law_data_biometric_ban` · `common/laws/ztr_data_policy.txt:47`

## Поля

- **group**: [[tr/Группы законов/Data Policy|Data Policy]]
- **icon**: `gfx/interface/icons/law_icons/law_data_biometric_ban.dds`
- **progressiveness**: `50`
- **unlocking_technologies**: [[tr/Технологии/Digital Governance|Digital Governance]]
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-political-strength-from-wealth-mult|state_political_strength_from_wealth_mult]] = `-0.25`
  - `goods_output_raw_data_mult` = `-0.5` → [[tr/Товары/Raw Data|Raw Data]]
  - `goods_output_ai_systems_mult` = `-0.75` → [[tr/Товары/AI Systems|AI Systems]]
  - [[vanilla/движок/Модификаторы C#^m-country-tech-research-speed-mult|country_tech_research_speed_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.1`
- **ai_enact_weight_modifier**: скрипт, строки 67–74

## Ссылаются

- **Идеологии** (lawgroup_data_policy: approve): [[tr/Идеологии/Extreme Progressist|Extreme Progressist]]
- **Идеологии** (lawgroup_data_policy: disapprove): [[tr/Идеологии/Neoliberal Progressist|Neoliberal Progressist]]
- **Идеологии** (lawgroup_data_policy: neutral): [[tr/Идеологии/Extreme Traditionalist|Extreme Traditionalist]], [[tr/Идеологии/Moderate Progressist|Moderate Progressist]], [[tr/Идеологии/Moderate Traditionalist|Moderate Traditionalist]]

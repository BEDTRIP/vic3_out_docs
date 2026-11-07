---
type: concept
description: "Закон «Basic Data Privacy» — T&R 1.13, `law_data_privacy_basic`"
project: vic3
source: tr
aliases: ["Basic Data Privacy", "law_data_privacy_basic"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_data_privacy_basic
paths: [TechRes+Kuromi/t&r/common/laws/ztr_data_policy.txt]
---
# Basic Data Privacy

Закон · `law_data_privacy_basic` · `common/laws/ztr_data_policy.txt:18`

## Поля

- **group**: [[tr/Группы законов/Data Policy|Data Policy]]
- **icon**: `gfx/interface/icons/law_icons/law_data_privacy_basic.dds`
- **progressiveness**: `25`
- **unlocking_technologies**: [[tr/Технологии/Raw Data Processing|Raw Data Processing]]
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-political-strength-from-wealth-mult|state_political_strength_from_wealth_mult]] = `-0.1`
  - `goods_output_raw_data_mult` = `-0.25` → [[tr/Товары/Raw Data|Raw Data]]
  - `goods_output_ai_systems_mult` = `-0.25` → [[tr/Товары/AI Systems|AI Systems]]
  - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.05`
  - [[vanilla/движок/Модификаторы S#^m-state-radicals-from-political-movements-mult|state_radicals_from_political_movements_mult]] = `-0.05`
- **ai_enact_weight_modifier**: скрипт, строки 37–44

## Ссылаются

- **Идеологии** (lawgroup_data_policy: approve): [[tr/Идеологии/Extreme Progressist|Extreme Progressist]], [[tr/Идеологии/Moderate Progressist|Moderate Progressist]], [[tr/Идеологии/Moderate Traditionalist|Moderate Traditionalist]]
- **Идеологии** (lawgroup_data_policy: neutral): [[tr/Идеологии/Extreme Traditionalist|Extreme Traditionalist]], [[tr/Идеологии/Neoliberal Progressist|Neoliberal Progressist]]

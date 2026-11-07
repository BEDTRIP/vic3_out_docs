---
type: concept
description: "Черта группы интересов «Philanthropy» — VC 1.13, `ig_trait_philanthropy`"
project: vic3
source: vc
aliases: ["Philanthropy", "ig_trait_philanthropy"]
tags: [VC, черта-группы-интересов]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ig_trait_philanthropy
paths: [VC/common/interest_group_traits/joi_group_traits.txt]
---
# Philanthropy

Черта группы интересов · `ig_trait_philanthropy` · `common/interest_group_traits/joi_group_traits.txt:737`

## Поля

- **icon**: `gfx/interface/icons/ig_trait_icons/job_creators.dds`
- **min_approval**: `loyal`
- **modifier**:
  - `state_education_access_add` = `0.05`
  - `building_university_throughput_add` = `0.15` → [[vanilla/Здания/Университеты|Университеты]]
  - `state_pollution_reduction_health_mult` = `-0.15`

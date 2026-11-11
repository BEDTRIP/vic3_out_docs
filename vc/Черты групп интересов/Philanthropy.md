---
type: concept
description: "Черта группы интересов «Philanthropy» — VC 1.15, `ig_trait_philanthropy`"
project: vic3
audience: agent
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
  - [[vanilla/движок/Модификаторы S#^m-state-education-access-add|state_education_access_add]] = `0.05`
  - [[vanilla/движок/Модификаторы B#^m-building-university-throughput-add|building_university_throughput_add]] = `0.15` → [[vanilla/Здания/Университеты|Университеты]]
  - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.15`

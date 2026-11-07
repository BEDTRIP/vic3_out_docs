---
type: concept
description: "Закон «Right to Euthanasia» — T&R 1.13, `law_euthanasia`"
project: vic3
audience: agent
source: tr
aliases: ["Right to Euthanasia", "law_euthanasia"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_euthanasia
paths: [TechRes+Kuromi/t&r/common/laws/ztr_bioethics.txt]
---
# Right to Euthanasia

Закон · `law_euthanasia` · `common/laws/ztr_bioethics.txt:47`

## Поля

- **group**: [[tr/Группы законов/Bioethics|Bioethics]]
- **icon**: `gfx/interface/icons/law_icons/law_euthanasia.dds`
- **progressiveness**: `25`
- **unlocking_technologies**: [[tr/Технологии/Counterculture|Counterculture]]
- **disallowing_laws**: [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]], [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]]
- **modifier**:
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-devout-pol-str-mult|interest_group_ig_devout_pol_str_mult]] = `-0.2`
  - [[vanilla/движок/Модификаторы I#^m-interest-group-ig-intelligentsia-pol-str-mult|interest_group_ig_intelligentsia_pol_str_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы P#^m-political-movement-radicalism-from-enactment-disapproval-mult|political_movement_radicalism_from_enactment_disapproval_mult]] = `0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-birth-rate-mult|state_birth_rate_mult]] = `0.02`
- **ai_enact_weight_modifier**: скрипт, строки 70–77

## Ссылаются

- **Идеологии** (lawgroup_bioethics: approve): [[tr/Идеологии/Extreme Progressist|Extreme Progressist]]
- **Идеологии** (lawgroup_bioethics: disapprove): [[tr/Идеологии/Extreme Traditionalist|Extreme Traditionalist]]
- **Идеологии** (lawgroup_bioethics: neutral): [[tr/Идеологии/Moderate Traditionalist|Moderate Traditionalist]]
- **Идеологии** (lawgroup_bioethics: strongly_approve): [[tr/Идеологии/Moderate Progressist|Moderate Progressist]], [[tr/Идеологии/Neoliberal Progressist|Neoliberal Progressist]]

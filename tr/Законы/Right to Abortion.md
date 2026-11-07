---
type: concept
description: "Закон «Right to Abortion» — T&R 1.13, `law_abortion`"
project: vic3
source: tr
aliases: ["Right to Abortion", "law_abortion"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_abortion
paths: [TechRes+Kuromi/t&r/common/laws/ztr_bioethics.txt]
---
# Right to Abortion

Закон · `law_abortion` · `common/laws/ztr_bioethics.txt:80`

## Поля

- **group**: [[tr/Группы законов/Bioethics|Bioethics]]
- **icon**: `gfx/interface/icons/law_icons/law_abortion.dds`
- **progressiveness**: `50`
- **unlocking_technologies**: [[tr/Технологии/Neo-Feminism|Neo-Feminism]]
- **disallowing_laws**: [[tr/Законы/Попечительство|Попечительство]], [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]], [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]]
- **modifier**:
  - `interest_group_ig_devout_pol_str_mult` = `-0.2`
  - `interest_group_ig_intelligentsia_pol_str_mult` = `0.2`
  - `state_working_adult_ratio_add` = `0.02`
  - `political_movement_radicalism_from_enactment_disapproval_mult` = `0.2`
- **ai_enact_weight_modifier**: скрипт, строки 105–112

## Ссылаются

- **Идеологии** (lawgroup_bioethics: approve): [[tr/Идеологии/Moderate Progressist|Moderate Progressist]]
- **Идеологии** (lawgroup_bioethics: disapprove): [[tr/Идеологии/Moderate Traditionalist|Moderate Traditionalist]]
- **Идеологии** (lawgroup_bioethics: strongly_approve): [[tr/Идеологии/Extreme Progressist|Extreme Progressist]], [[tr/Идеологии/Neoliberal Progressist|Neoliberal Progressist]]
- **Идеологии** (lawgroup_bioethics: strongly_disapprove): [[tr/Идеологии/Extreme Traditionalist|Extreme Traditionalist]]

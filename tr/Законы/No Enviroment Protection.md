---
type: concept
description: "Закон «No Enviroment Protection» — T&R 1.13, `law_no_protection`"
project: vic3
audience: agent
source: tr
aliases: ["No Enviroment Protection", "law_no_protection"]
tags: [tr, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_no_protection
paths: [TechRes+Kuromi/t&r/common/laws/ztr_environmental_policy.txt]
---
# No Enviroment Protection

Закон · `law_no_protection` · `common/laws/ztr_environmental_policy.txt:1`

## Поля

- **group**: [[tr/Группы законов/Environmental Policy|Environmental Policy]]
- **icon**: `gfx/interface/icons/law_icons/law_no_protection.dds`
- **progressiveness**: `0`
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `0.05`
- **ai_enact_weight_modifier**: скрипт, строки 12–19

## Ссылаются

- **Идеологии** (lawgroup_environmental_policy: disapprove): [[tr/Идеологии/Moderate Environmentalist|Moderate Environmentalist]]
- **Идеологии** (lawgroup_environmental_policy: neutral): [[tr/Идеологии/Negligent Environmentalist|Negligent Environmentalist]], [[tr/Идеологии/Neoliberal Environmentalist|Neoliberal Environmentalist]]
- **Идеологии** (lawgroup_environmental_policy: strongly_disapprove): [[tr/Идеологии/Extreme Environmentalist|Extreme Environmentalist]]
- **Методы производства** (запрещает закон): [[tr/Методы производства/Aluminium Recycling|Aluminium Recycling]], [[tr/Методы производства/Carbon Capture|Carbon Capture]], [[tr/Методы производства/Mixed Recycling|Mixed Recycling]], [[tr/Методы производства/Paper Recycling|Paper Recycling]], [[tr/Методы производства/Plastics Recycling|Plastics Recycling]], [[tr/Методы производства/Steel Recycling|Steel Recycling]]

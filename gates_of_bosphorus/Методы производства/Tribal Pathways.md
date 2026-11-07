---
type: concept
description: "Метод производства «Tribal Pathways» — Gates of Bosphorus 1.13, `pm_gbbf_tribal_paths`"
project: vic3
source: gates_of_bosphorus
aliases: ["Tribal Pathways", "pm_gbbf_tribal_paths"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_tribal_paths
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Tribal Pathways

Метод производства · `pm_gbbf_tribal_paths` · `common/production_methods/gbbf_07_government_methods.txt:373`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/intensive_grazing.dds`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_aristocrats_add` = `100` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - `building_employment_laborers_add` = `900` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `5`
    - `state_trade_capacity_add` = `5`
    - `state_weekly_trades_add` = `1`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Saharan Pathways|Saharan Pathways]]

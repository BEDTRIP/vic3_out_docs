---
type: concept
description: "Метод производства «Unpaved Roads» — Gates of Bosphorus 1.13, `pm_gbbf_unpaved_roads`"
project: vic3
source: gates_of_bosphorus
aliases: ["Unpaved Roads", "pm_gbbf_unpaved_roads"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_unpaved_roads
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Unpaved Roads

Метод производства · `pm_gbbf_unpaved_roads` · `common/production_methods/gbbf_07_government_methods.txt:73`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/picks_and_shovels.dds`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_laborers_add` = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerks_add` = `300` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `5`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Road Surfacing|Road Surfacing]]

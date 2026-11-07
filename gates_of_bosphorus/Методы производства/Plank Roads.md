---
type: concept
description: "Метод производства «Plank Roads» — Gates of Bosphorus 1.13, `pm_gbbf_plank_roads`"
project: vic3
source: gates_of_bosphorus
aliases: ["Plank Roads", "pm_gbbf_plank_roads"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_plank_roads
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Plank Roads

Метод производства · `pm_gbbf_plank_roads` · `common/production_methods/gbbf_07_government_methods.txt:89`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wooden_buildings.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Сталелитейные заводы|Сталелитейные заводы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_wood_add` = `5` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_tools_add` = `2` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_transportation_add` = `10` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_clerks_add` = `300` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `10`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Road Surfacing|Road Surfacing]]

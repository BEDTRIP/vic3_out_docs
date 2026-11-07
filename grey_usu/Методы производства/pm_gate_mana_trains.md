---
type: concept
description: "Метод производства «pm_gate_mana_trains» — grey USU 1.13, `pm_gate_mana_trains`"
project: vic3
source: grey_usu
aliases: ["pm_gate_mana_trains"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gate_mana_trains
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/zzMoG_USU_manaflow_compat_pms.txt]
---
# pm_gate_mana_trains

Метод производства · `pm_gate_mana_trains` · `common/production_methods/zzMoG_USU_manaflow_compat_pms.txt:44`

## Поля

- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_gate_mana_core_add` = `-3`
    - `goods_input_gate_mana_add` = `3`
    - `goods_input_engines_add` = `1` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_output_transportation_add` = `25` → [[grey_usu/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-600` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `-1400` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_clerks_add` = `-550` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **unscaled**:
    - `state_market_access_price_impact` = `0.03`
  - **workforce_scaled**:
    - `state_infrastructure_add` = `-15`
    - `state_pollution_generation_add` = `3`
  - **level_scaled**:
    - `state_infrastructure_add` = `10`

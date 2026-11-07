---
type: concept
description: "Метод производства «Paved Roads» — Gates of Bosphorus 1.13, `pm_gbbf_paved_roads`"
project: vic3
source: gates_of_bosphorus
aliases: ["Paved Roads", "pm_gbbf_paved_roads"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_paved_roads
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Paved Roads

Метод производства · `pm_gbbf_paved_roads` · `common/production_methods/gbbf_07_government_methods.txt:420`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/automobiles.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Мощёные дороги|Мощёные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_oil_add` = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_transportation_add` = `15` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_bureaucrats_add` = `200` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - `building_employment_clerks_add` = `300` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `15`
    - `state_trade_capacity_add` = `10`
    - `state_weekly_trades_add` = `1`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Saharan Pathways|Saharan Pathways]]

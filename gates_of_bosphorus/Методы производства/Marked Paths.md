---
type: concept
description: "Метод производства «Marked Paths» — Gates of Bosphorus 1.13, `pm_gbbf_marked_paths`"
project: vic3
source: gates_of_bosphorus
aliases: ["Marked Paths", "pm_gbbf_marked_paths"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_marked_paths
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Marked Paths

Метод производства · `pm_gbbf_marked_paths` · `common/production_methods/gbbf_07_government_methods.txt:391`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/open_air_stockyards.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Сталелитейные заводы|Сталелитейные заводы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_wood_add` = `5` → [[vanilla/Товары/Древесина|Древесина]]
    - `goods_input_tools_add` = `2` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_transportation_add` = `10` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_aristocrats_add` = `200` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - `building_employment_clerks_add` = `300` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_infrastructure_add` = `10`
    - `state_trade_capacity_add` = `5`
    - `state_weekly_trades_add` = `1`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Saharan Pathways|Saharan Pathways]]

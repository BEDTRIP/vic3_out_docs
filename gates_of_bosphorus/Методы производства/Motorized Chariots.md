---
type: concept
description: "Метод производства «Motorized Chariots» — Gates of Bosphorus 1.13, `pm_gbbf_motorized_chariots`"
project: vic3
source: gates_of_bosphorus
aliases: ["Motorized Chariots", "pm_gbbf_motorized_chariots"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_motorized_chariots
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Motorized Chariots

Метод производства · `pm_gbbf_motorized_chariots` · `common/production_methods/gbbf_08_monuments_methods.txt:242`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_motorized_chariots.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_radicals_from_political_movements_mult` = `-0.05`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_steel_add` = `10` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_automobiles_add` = `5` → [[vanilla/Товары/Автомобили|Автомобили]]
    - `goods_input_oil_add` = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `250` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Chariot Construction|Chariot Construction]]

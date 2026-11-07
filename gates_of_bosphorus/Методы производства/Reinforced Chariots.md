---
type: concept
description: "Метод производства «Reinforced Chariots» — Gates of Bosphorus 1.13, `pm_gbbf_reinforced_chariots`"
project: vic3
source: gates_of_bosphorus
aliases: ["Reinforced Chariots", "pm_gbbf_reinforced_chariots"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_reinforced_chariots
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Reinforced Chariots

Метод производства · `pm_gbbf_reinforced_chariots` · `common/production_methods/gbbf_08_monuments_methods.txt:202`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_reinforced_chariots.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_radicals_from_political_movements_mult` = `-0.01`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_iron_add` = `20` → [[vanilla/Товары/Железо|Железо]]
    - `goods_input_tools_add` = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Chariot Construction|Chariot Construction]]

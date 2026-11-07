---
type: concept
description: "Метод производства «Drawn Carts» — Gates of Bosphorus 1.13, `pm_gbbf_drawn_carts`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Drawn Carts", "pm_gbbf_drawn_carts"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_drawn_carts
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Drawn Carts

Метод производства · `pm_gbbf_drawn_carts` · `common/production_methods/gbbf_07_government_methods.txt:452`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_automation_log_carts.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Механические инструменты|Механические инструменты]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-wood-add|goods_input_wood_add]] = `3` → [[vanilla/Товары/Древесина|Древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `2` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `5` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `5`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Mode of Transportation|Mode of Transportation]]

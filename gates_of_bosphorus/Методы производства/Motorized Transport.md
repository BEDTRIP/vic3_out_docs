---
type: concept
description: "Метод производства «Motorized Transport» — Gates of Bosphorus 1.13, `pm_gbbf_motor_carts`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Motorized Transport", "pm_gbbf_motor_carts"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_motor_carts
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Motorized Transport

Метод производства · `pm_gbbf_motor_carts` · `common/production_methods/gbbf_07_government_methods.txt:500`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_automation_motorized.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Двигатель внутреннего сгорания|Двигатель внутреннего сгорания]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-automobiles-add|goods_input_automobiles_add]] = `5` → [[vanilla/Товары/Автомобили|Автомобили]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `15` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `300` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `15`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Mode of Transportation|Mode of Transportation]]

---
type: concept
description: "Метод производства «Motor Cars» — Gates of Bosphorus 1.13, `pm_gbbf_motor_cars`"
project: vic3
source: gates_of_bosphorus
aliases: ["Motor Cars", "pm_gbbf_motor_cars"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_motor_cars
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Motor Cars

Метод производства · `pm_gbbf_motor_cars` · `common/production_methods/gbbf_07_government_methods.txt:192`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/automobiles.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Двигатель внутреннего сгорания|Двигатель внутреннего сгорания]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-automobiles-add|goods_input_automobiles_add]] = `5` → [[vanilla/Товары/Автомобили|Автомобили]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `15` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `300` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `15`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Mode of Transport|Mode of Transport]]

---
type: concept
description: "Метод производства «Asphalt Roads» — Gates of Bosphorus 1.13, `pm_gbbf_asphalt_roads`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Asphalt Roads", "pm_gbbf_asphalt_roads"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_asphalt_roads
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Asphalt Roads

Метод производства · `pm_gbbf_asphalt_roads` · `common/production_methods/gbbf_07_government_methods.txt:115`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/steel_tools.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Мощёные дороги|Мощёные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `5` → [[vanilla/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `15` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `300` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `15`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Road Surfacing|Road Surfacing]]

---
type: concept
description: "Метод производства «Basic Hydropower» — Gates of Bosphorus 1.13, `pm_gbbf_basic_hydropower`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Basic Hydropower", "pm_gbbf_basic_hydropower"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_basic_hydropower
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Basic Hydropower

Метод производства · `pm_gbbf_basic_hydropower` · `common/production_methods/gbbf_07_government_methods.txt:270`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_basic_hydropower.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Производство электричества|Производство электричества]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `50` → [[vanilla/Товары/Электричество|Электричество]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `400` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `400` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `200` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Power Production|Power Production]]

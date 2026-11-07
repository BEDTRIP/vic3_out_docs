---
type: concept
description: "Метод производства «Water-tube Boiler» — Gates of Bosphorus 1.13, `gbbf_watertube_boiler_building_esparto`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Water-tube Boiler", "gbbf_watertube_boiler_building_esparto"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: gbbf_watertube_boiler_building_esparto
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_04_plantation_methods.txt]
---
# Water-tube Boiler

Метод производства · `gbbf_watertube_boiler_building_esparto` · `common/production_methods/gbbf_04_plantation_methods.txt:102`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/watertube_boiler.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **disallowing_laws**: [[vanilla/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `5` → [[vanilla/Товары/Уголь|Уголь]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Automation|Automation]]

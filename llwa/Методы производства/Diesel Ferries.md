---
type: concept
description: "Метод производства «Diesel Ferries» — LLWA 1.13, `LLWA_pm_motor_ferries`"
project: vic3
source: llwa
aliases: ["Diesel Ferries", "LLWA_pm_motor_ferries"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_motor_ferries
paths: [llwa/common/production_methods/LLWA_water.txt]
---
# Diesel Ferries

Метод производства · `LLWA_pm_motor_ferries` · `common/production_methods/LLWA_water.txt:198`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_motor_ferries.dds`
- **unlocking_production_methods**: [[llwa/Методы производства/Sail-steamships|Sail-steamships]], [[llwa/Методы производства/Steamships|Steamships]], [[llwa/Методы производства/Motor Vessels|Motor Vessels]]
- **unlocking_technologies**: [[vanilla/Технологии/Компрессионное зажигание|Компрессионное зажигание]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steamers-add|goods_input_steamers_add]] = `2` → [[vanilla/Товары/Пароходы|Пароходы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `2` → [[vanilla/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `20` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Passenger Vessels|Passenger Vessels]]

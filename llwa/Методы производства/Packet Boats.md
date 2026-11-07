---
type: concept
description: "Метод производства «Packet Boats» — LLWA 1.13, `LLWA_pm_packet_ships`"
project: vic3
source: llwa
aliases: ["Packet Boats", "LLWA_pm_packet_ships"]
tags: [LLWA, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: LLWA_pm_packet_ships
paths: [llwa/common/production_methods/LLWA_water.txt]
---
# Packet Boats

Метод производства · `LLWA_pm_packet_ships` · `common/production_methods/LLWA_water.txt:135`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/LLWA_packet_boats.dds`
- **unlocking_production_methods**: [[llwa/Методы производства/Sail-steamships|Sail-steamships]], [[llwa/Методы производства/Steamships|Steamships]], [[llwa/Методы производства/Motor Vessels|Motor Vessels]]
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-clippers-add|goods_input_clippers_add]] = `2` → [[vanilla/Товары/Клипперы|Клипперы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `1` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `1` → [[vanilla/Товары/Уголь|Уголь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `10` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `100` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `20`

## Ссылаются

- **Группы методов** (методы группы): [[llwa/Группы методов/Passenger Vessels|Passenger Vessels]]

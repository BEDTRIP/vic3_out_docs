---
type: concept
description: "Метод производства «Aluminium Passenger Carriages» — T&R 1.13, `pm_aluminium_passenger_carriages`"
project: vic3
audience: agent
source: tr
aliases: ["Aluminium Passenger Carriages", "pm_aluminium_passenger_carriages"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_aluminium_passenger_carriages
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Aluminium Passenger Carriages

Метод производства · `pm_aluminium_passenger_carriages` · `common/production_methods/ztr_new_production_methods.txt:9883`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_aluminium_passenger_carriages.dds`
- **unlocking_technologies**: [[tr/Технологии/Bayer Process|Bayer Process]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_aluminium_add` = `5` → [[tr/Товары/Aluminium|Aluminium]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `20` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Пассажирские поезда|Пассажирские поезда]]

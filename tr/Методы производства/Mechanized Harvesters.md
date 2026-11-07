---
type: concept
description: "Метод производства «Mechanized Harvesters» — T&R 1.13, `pm_mechanized_harvesters`"
project: vic3
audience: agent
source: tr
aliases: ["Mechanized Harvesters", "pm_mechanized_harvesters"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mechanized_harvesters
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Mechanized Harvesters

Метод производства · `pm_mechanized_harvesters` · `common/production_methods/ztr_new_production_methods.txt:10108`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/mechanized_harvesters.dds`
- **unlocking_technologies**: [[tr/Технологии/Heavy Machinery|Heavy Machinery]]
- **disallowing_laws**: [[tr/Законы/Запрет промышленности|Запрет промышленности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `4` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_light_fuel_add` = `1` → [[tr/Товары/Light Fuel|Light Fuel]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `2` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_robotics_add` = `1` → [[tr/Товары/Robotics|Robotics]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.5`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `-250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `-250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Специальное снаряжение|Специальное снаряжение]]

---
type: concept
description: "Метод производства «Advanced Turbine Generators (pm_advanced_turbine_generators)» — T&R 1.13, `pm_advanced_turbine_generators`"
project: vic3
source: tr
aliases: ["Advanced Turbine Generators (pm_advanced_turbine_generators)", "Advanced Turbine Generators", "pm_advanced_turbine_generators"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_turbine_generators
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Advanced Turbine Generators (pm_advanced_turbine_generators)

Метод производства · `pm_advanced_turbine_generators` · `common/production_methods/ztr_energy_production_methods.txt:62`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_advanced_turbine_generators.dds`
- **replacement_if_valid**: [[tr/Методы производства/Advanced Turbine Generators (pm_advanced_turbine_generators_2)|Advanced Turbine Generators (pm_advanced_turbine_generators_2)]]
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[vanilla/Технологии/ГСМ-турбина|ГСМ-турбина]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_steel_add` = `75` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_batteries_add` = `10` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_engines_add` = `30` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_copperwires_add` = `10` → [[tr/Товары/Wires|Wires]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_output_electricity_add` = `420` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `43` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `4500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/Local Electricity Systems|Local Electricity Systems]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Hydroelectric Power Plant|Hydroelectric Power Plant]]

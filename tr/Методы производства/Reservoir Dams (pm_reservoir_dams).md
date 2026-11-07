---
type: concept
description: "Метод производства «Reservoir Dams (pm_reservoir_dams)» — T&R 1.13, `pm_reservoir_dams`"
project: vic3
source: tr
aliases: ["Reservoir Dams (pm_reservoir_dams)", "Reservoir Dams", "pm_reservoir_dams"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_reservoir_dams
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Reservoir Dams (pm_reservoir_dams)

Метод производства · `pm_reservoir_dams` · `common/production_methods/ztr_energy_production_methods.txt:31`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/hydroelectric_plant.dds`
- **replacement_if_valid**: [[tr/Методы производства/Reservoir Dams (pm_reservoir_dams_2)|Reservoir Dams (pm_reservoir_dams_2)]]
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: [[vanilla/Технологии/Пневматические инструменты|Пневматические инструменты]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_steel_add` = `50` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_batteries_add` = `10` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_engines_add` = `20` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_copperwires_add` = `10` → [[tr/Товары/Wires|Wires]]
    - `goods_output_electricity_add` = `285` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_global_electricity_add` = `29` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_machinists_add` = `4250` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]
- **unlocking_laws**: [[tr/Законы/Local Electricity Systems|Local Electricity Systems]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Hydroelectric Power Plant|Hydroelectric Power Plant]]

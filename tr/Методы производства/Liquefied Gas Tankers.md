---
type: concept
description: "Метод производства «Liquefied Gas Tankers» — T&R 1.13, `pm_liquefied_gas_tankers`"
project: vic3
source: tr
aliases: ["Liquefied Gas Tankers", "pm_liquefied_gas_tankers"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_liquefied_gas_tankers
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Liquefied Gas Tankers

Метод производства · `pm_liquefied_gas_tankers` · `common/production_methods/ztr_new_production_methods.txt:7613`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gas_tanker_cars.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[tr/Технологии/Gas Liquefaction|Gas Liquefaction]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_transportation_add` = `10` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Transport (pmg_transportation_building_natural_gas_rig)|Transport (pmg_transportation_building_natural_gas_rig)]]

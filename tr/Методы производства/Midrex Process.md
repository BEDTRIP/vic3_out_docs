---
type: concept
description: "Метод производства «Midrex Process» — T&R 1.13, `pm_direct_reduced_iron_midrex_process`"
project: vic3
source: tr
aliases: ["Midrex Process", "pm_direct_reduced_iron_midrex_process"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_direct_reduced_iron_midrex_process
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Midrex Process

Метод производства · `pm_direct_reduced_iron_midrex_process` · `common/production_methods/ztr_new_production_methods.txt:182`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_direct_reduced_iron_midrex_process.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `-10`
- **unlocking_technologies**: [[tr/Технологии/Advanced Electric Arc Processes|Advanced Electric Arc Processes]]
- **unlocking_production_methods**: [[tr/Методы производства/Дуговая сталеплавильная печь|Дуговая сталеплавильная печь]], [[tr/Методы производства/Oxygen Steelmaking Furnace|Oxygen Steelmaking Furnace]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_gas_add` = `15` → [[tr/Товары/Natural Gas|Natural Gas]]
    - `goods_input_coal_add` = `-10` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_input_electricity_add` = `-15` → [[vanilla/Товары/Электричество|Электричество]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Direct Reduced Iron|Direct Reduced Iron]]

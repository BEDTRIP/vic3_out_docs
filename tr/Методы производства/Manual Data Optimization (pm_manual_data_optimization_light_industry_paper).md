---
type: concept
description: "Метод производства «Manual Data Optimization (pm_manual_data_optimization_light_industry_paper)» — T&R 1.13, `pm_manual_data_optimization_light_industry_paper`"
project: vic3
audience: agent
source: tr
aliases: ["Manual Data Optimization (pm_manual_data_optimization_light_industry_paper)", "Manual Data Optimization", "pm_manual_data_optimization_light_industry_paper"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_manual_data_optimization_light_industry_paper
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Manual Data Optimization (pm_manual_data_optimization_light_industry_paper)

Метод производства · `pm_manual_data_optimization_light_industry_paper` · `common/production_methods/ztr_data_production_methods.txt:1315`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_manual_data_optimization.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Корпоративное управление|Корпоративное управление]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-paper-add|goods_output_paper_add]] = `-1` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_business_data_add` = `1` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_organized_data_add` = `1` → [[tr/Товары/Organized Data|Organized Data]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-throughput-add|building_throughput_add]] = `0.075`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Optimization (pmg_data_optimization_light_industry_paper)|Optimization (pmg_data_optimization_light_industry_paper)]]

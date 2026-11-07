---
type: concept
description: "Метод производства «Manual Data Optimization (pm_manual_data_optimization_heavy_industry)» — T&R 1.13, `pm_manual_data_optimization_heavy_industry`"
project: vic3
source: tr
aliases: ["Manual Data Optimization (pm_manual_data_optimization_heavy_industry)", "Manual Data Optimization", "pm_manual_data_optimization_heavy_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_manual_data_optimization_heavy_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Manual Data Optimization (pm_manual_data_optimization_heavy_industry)

Метод производства · `pm_manual_data_optimization_heavy_industry` · `common/production_methods/ztr_data_production_methods.txt:1476`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_manual_data_optimization.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Корпоративное управление|Корпоративное управление]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_paper_add` = `1` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_business_data_add` = `1` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_organized_data_add` = `1.5` → [[tr/Товары/Organized Data|Organized Data]]
  - **unscaled**:
    - `building_throughput_add` = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Optimization (pmg_data_optimization_heavy_industry_algorithmic_dispatch)|Data Optimization (pmg_data_optimization_heavy_industry_algorithmic_dispatch)]], [[tr/Группы методов/Data Optimization (pmg_data_optimization_heavy_industry_algorithmic_dispatch_no_shopkeepers)|Data Optimization (pmg_data_optimization_heavy_industry_algorithmic_dispatch_no_shopkeepers)]], [[tr/Группы методов/Data Optimization (pmg_data_optimization_heavy_industry_no_shopkeepers)|Data Optimization (pmg_data_optimization_heavy_industry_no_shopkeepers)]], [[tr/Группы методов/Optimization (pmg_data_optimization_heavy_industry)|Optimization (pmg_data_optimization_heavy_industry)]], [[tr/Группы методов/Optimization (pmg_data_optimization_heavy_industry_computer)|Optimization (pmg_data_optimization_heavy_industry_computer)]], [[tr/Группы методов/Optimization (pmg_data_optimization_heavy_industry_software)|Optimization (pmg_data_optimization_heavy_industry_software)]], [[tr/Группы методов/Optimization (pmg_data_optimization_heavy_industry_telecommunications)|Optimization (pmg_data_optimization_heavy_industry_telecommunications)]]

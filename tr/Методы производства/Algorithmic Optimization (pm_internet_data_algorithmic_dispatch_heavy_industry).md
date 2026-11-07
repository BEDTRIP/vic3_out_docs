---
type: concept
description: "Метод производства «Algorithmic Optimization (pm_internet_data_algorithmic_dispatch_heavy_industry)» — T&R 1.13, `pm_internet_data_algorithmic_dispatch_heavy_industry`"
project: vic3
source: tr
aliases: ["Algorithmic Optimization (pm_internet_data_algorithmic_dispatch_heavy_industry)", "Algorithmic Optimization", "pm_internet_data_algorithmic_dispatch_heavy_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_data_algorithmic_dispatch_heavy_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Algorithmic Optimization (pm_internet_data_algorithmic_dispatch_heavy_industry)

Метод производства · `pm_internet_data_algorithmic_dispatch_heavy_industry` · `common/production_methods/ztr_data_production_methods.txt:1668`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_neural_model_training_i_o.dds`
- **unlocking_technologies**: [[tr/Технологии/Algorithmic Dispatch|Algorithmic Dispatch]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_ai_systems_add` = `6` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_softwares_add` = `2` → [[tr/Товары/Software|Software]]
    - `goods_input_telecommunications_add` = `4` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_business_data_add` = `4` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_raw_data_add` = `16` → [[tr/Товары/Raw Data|Raw Data]]
  - **unscaled**:
    - `building_throughput_add` = `1.8`
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `-100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Data Optimization (pmg_data_optimization_heavy_industry_algorithmic_dispatch)|Data Optimization (pmg_data_optimization_heavy_industry_algorithmic_dispatch)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_automotive_industry)|IoT Assembly Lines (pm_iot_building_automotive_industry)]], [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_consumer_electronics_industry)|IoT Assembly Lines (pm_iot_building_consumer_electronics_industry)]]

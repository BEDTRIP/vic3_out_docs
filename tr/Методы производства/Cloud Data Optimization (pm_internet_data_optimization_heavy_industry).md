---
type: concept
description: "Метод производства «Cloud Data Optimization (pm_internet_data_optimization_heavy_industry)» — T&R 1.13, `pm_internet_data_optimization_heavy_industry`"
project: vic3
source: tr
aliases: ["Cloud Data Optimization (pm_internet_data_optimization_heavy_industry)", "Cloud Data Optimization", "pm_internet_data_optimization_heavy_industry"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_internet_data_optimization_heavy_industry
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Cloud Data Optimization (pm_internet_data_optimization_heavy_industry)

Метод производства · `pm_internet_data_optimization_heavy_industry` · `common/production_methods/ztr_data_production_methods.txt:1599`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_internet_data_optimization.dds`
- **unlocking_technologies**: [[tr/Технологии/Big Data Analytics|Big Data Analytics]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_ai_systems_add` = `2` → [[tr/Товары/AI Systems|AI Systems]]
    - `goods_input_softwares_add` = `4` → [[tr/Товары/Software|Software]]
    - `goods_input_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_business_data_add` = `6` → [[tr/Товары/Business Data|Business Data]]
    - `goods_output_raw_data_add` = `16` → [[tr/Товары/Raw Data|Raw Data]]
  - **unscaled**:
    - `building_throughput_add` = `1.8`
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `-100` → [[vanilla/Население/Типы/Лавочники|Лавочники]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Optimization (pmg_data_optimization_heavy_industry)|Optimization (pmg_data_optimization_heavy_industry)]], [[tr/Группы методов/Optimization (pmg_data_optimization_heavy_industry_computer)|Optimization (pmg_data_optimization_heavy_industry_computer)]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_commonalloys_plant)|IoT Assembly Lines (pm_iot_building_commonalloys_plant)]], [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_computer_assembly)|IoT Assembly Lines (pm_iot_building_computer_assembly)]], [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_electrics_industry)|IoT Assembly Lines (pm_iot_building_electrics_industry)]], [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_motor_industry)|IoT Assembly Lines (pm_iot_building_motor_industry)]], [[tr/Методы производства/IoT Assembly Lines (pm_iot_building_steel_mill)|IoT Assembly Lines (pm_iot_building_steel_mill)]]

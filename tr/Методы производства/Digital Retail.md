---
type: concept
description: "Метод производства «Digital Retail» — T&R 1.13, `pm_digital_retail`"
project: vic3
source: tr
aliases: ["Digital Retail", "pm_digital_retail"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_digital_retail
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Digital Retail

Метод производства · `pm_digital_retail` · `common/production_methods/ztr_new_production_methods.txt:6787`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_digital_retail_iot.dds`
- **unlocking_technologies**: [[tr/Технологии/E-Commerce|E-Commerce]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_glass_add` = `2` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_steel_add` = `1` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_telecommunications_add` = `1` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_electricity_add` = `1` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_on_demand_goods_add` = `1` → [[tr/Товары/On-Demand Goods|On-Demand Goods]]
    - `goods_output_services_add` = `35` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_clerks_add` = `750` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_shopkeepers_add` = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Блага|Блага]]

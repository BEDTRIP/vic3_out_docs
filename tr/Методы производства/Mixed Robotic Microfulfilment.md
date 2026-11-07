---
type: concept
description: "Метод производства «Mixed Robotic Microfulfilment» — T&R 1.13, `pm_mixed_robotic_microfulfilment`"
project: vic3
source: tr
aliases: ["Mixed Robotic Microfulfilment", "pm_mixed_robotic_microfulfilment"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mixed_robotic_microfulfilment
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# Mixed Robotic Microfulfilment

Метод производства · `pm_mixed_robotic_microfulfilment` · `common/production_methods/ztr_data_production_methods.txt:1003`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/microfulfilment_robotics.dds`
- **unlocking_technologies**: [[tr/Технологии/IoT-Driven Manufacturing|IoT-Driven Manufacturing]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_clothes_add` = `4` → [[tr/Товары/Одежда|Одежда]]
    - `goods_input_manzoni_prints_add` = `3` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_cosmetics_add` = `3` → [[tr/Товары/Cosmetics|Cosmetics]]
    - `goods_input_homeappliances_add` = `1` → [[tr/Товары/Home Appliances|Home Appliances]]
    - `goods_input_furniture_add` = `1` → [[vanilla/Товары/Мебель|Мебель]]
    - `goods_input_computer_add` = `1` → [[tr/Товары/Computers|Computers]]
    - `goods_input_televisions_add` = `1` → [[tr/Товары/Televisions|Televisions]]
    - `goods_input_telephones_add` = `3` → [[vanilla/Товары/Телефоны|Телефоны]]
  - **level_scaled**:
    - `building_employment_clerks_add` = `-250` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_machinists_add` = `-400` → [[vanilla/Население/Типы/Механики|Механики]]
- **unlocking_production_methods**: [[tr/Методы производства/Integrated Retail E-Commerce|Integrated Retail E-Commerce]], [[tr/Методы производства/Predictive Fulfilment Network|Predictive Fulfilment Network]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Fulfilment Type|Fulfilment Type]]

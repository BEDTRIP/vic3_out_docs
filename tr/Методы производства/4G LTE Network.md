---
type: concept
description: "Метод производства «4G LTE Network» — T&R 1.13, `pm_4g_lte_network`"
project: vic3
source: tr
aliases: ["4G LTE Network", "pm_4g_lte_network"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_4g_lte_network
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# 4G LTE Network

Метод производства · `pm_4g_lte_network` · `common/production_methods/ztr_data_production_methods.txt:830`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_4g_network.dds`
- **unlocking_technologies**: [[tr/Технологии/Mobile Devices|Mobile Devices]]
- **unlocking_production_methods**: [[tr/Методы производства/Internet Global Network|Internet Global Network]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `10` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_softwares_add` = `2` → [[tr/Товары/Software|Software]]
    - `goods_input_processors_add` = `1` → [[tr/Товары/Processors|Processors]]
    - `goods_output_telecommunications_add` = `30` → [[tr/Товары/Telecommunications|Telecommunications]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Wireless Telecommunications|Wireless Telecommunications]]

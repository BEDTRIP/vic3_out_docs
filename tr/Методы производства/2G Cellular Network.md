---
type: concept
description: "Метод производства «2G Cellular Network» — T&R 1.13, `pm_2g_digital_cellular`"
project: vic3
source: tr
aliases: ["2G Cellular Network", "pm_2g_digital_cellular"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_2g_digital_cellular
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_data_production_methods.txt]
---
# 2G Cellular Network

Метод производства · `pm_2g_digital_cellular` · `common/production_methods/ztr_data_production_methods.txt:814`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_2g_network.dds`
- **unlocking_technologies**: [[tr/Технологии/Broadband & Wireless Networks|Broadband & Wireless Networks]]
- **unlocking_production_methods**: [[tr/Методы производства/Internet Global Network|Internet Global Network]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `5` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_telecommunications_add` = `5` → [[tr/Товары/Telecommunications|Telecommunications]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Wireless Telecommunications|Wireless Telecommunications]]

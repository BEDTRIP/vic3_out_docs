---
type: concept
description: "Метод производства «Digital Printers» — T&R 1.13, `pm_digital_press`"
project: vic3
audience: agent
source: tr
aliases: ["Digital Printers", "pm_digital_press"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_digital_press
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Digital Printers

Метод производства · `pm_digital_press` · `common/production_methods/ztr_new_production_methods.txt:9428`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_digital_press.dds`
- **unlocking_technologies**: [[tr/Технологии/User Interface|User Interface]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `50` → [[vanilla/Товары/Бумага|Бумага]]
    - `goods_input_computer_add` = `10` → [[tr/Товары/Computers|Computers]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-dye-add|goods_input_dye_add]] = `15` → [[vanilla/Товары/Красители|Красители]]
    - `goods_input_robotics_add` = `5` → [[tr/Товары/Robotics|Robotics]]
    - `goods_input_softwares_add` = `5` → [[tr/Товары/Software|Software]]
    - `goods_output_manzoni_prints_add` = `115` → [[tr/Товары/Media Content|Media Content]]
- **unlocking_production_methods**: [[tr/Методы производства/Early Publishing Communication|Early Publishing Communication]], [[tr/Методы производства/Mid Publishing Communication|Mid Publishing Communication]], [[tr/Методы производства/Late Publishing Communication|Late Publishing Communication]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Prints Production|Prints Production]]

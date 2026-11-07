---
type: concept
description: "Метод производства «Computer Teleprinters» — T&R 1.13, `pm_computer_teleprinters`"
project: vic3
source: tr
aliases: ["Computer Teleprinters", "pm_computer_teleprinters"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_computer_teleprinters
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Computer Teleprinters

Метод производства · `pm_computer_teleprinters` · `common/production_methods/ztr_new_production_methods.txt:4535`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_computer_teleprinters.dds`
- **unlocking_technologies**: [[tr/Технологии/Computers|Computers]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `5` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_copperwires_add` = `15` → [[tr/Товары/Wires|Wires]]
    - `goods_input_batteries_add` = `5` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_alloys_add` = `15` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_electroniccomponents_add` = `20` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_processors_add` = `5` → [[tr/Товары/Processors|Processors]]
    - `goods_output_computer_add` = `40` → [[tr/Товары/Computers|Computers]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1500` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2250` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Computer|Computer]]

---
type: concept
description: "Метод производства «Laptops» — T&R 1.13, `pm_laptops`"
project: vic3
audience: agent
source: tr
aliases: ["Laptops", "pm_laptops"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_laptops
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Laptops

Метод производства · `pm_laptops` · `common/production_methods/ztr_new_production_methods.txt:4589`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_laptops.dds`
- **unlocking_technologies**: [[tr/Технологии/Mobile Devices|Mobile Devices]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `5` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_batteries_add` = `15` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_softwares_add` = `25` → [[tr/Товары/Software|Software]]
    - `goods_input_televisions_add` = `5` → [[tr/Товары/Televisions|Televisions]]
    - `goods_input_processors_add` = `25` → [[tr/Товары/Processors|Processors]]
    - `goods_output_computer_add` = `70` → [[tr/Товары/Computers|Computers]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1500` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2250` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Computer|Computer]]

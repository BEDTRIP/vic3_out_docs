---
type: concept
description: "Метод производства «Electric Instruments» — T&R 1.13, `pm_elgar_electric_instruments`"
project: vic3
source: tr
aliases: ["Electric Instruments", "pm_elgar_electric_instruments"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_elgar_electric_instruments
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Electric Instruments

Метод производства · `pm_elgar_electric_instruments` · `common/production_methods/ztr_modified_mr_production_methods.txt:385`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/elgar_electric_instruments_pm.dds`
- **unlocking_technologies**: [[tr/Технологии/Rock & Roll|Rock & Roll]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_alloys_add` = `15` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_plastics_add` = `5` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_electroniccomponents_add` = `2` → [[tr/Товары/Electronic Components|Electronic Components]]
    - `goods_input_tools_add` = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_output_elgar_instruments_add` = `60` → [[tr/Товары/Instruments|Instruments]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Musical Instruments|Musical Instruments]]

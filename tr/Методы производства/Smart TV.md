---
type: concept
description: "Метод производства «Smart TV» — T&R 1.13, `pm_smart_televisions`"
project: vic3
audience: agent
source: tr
aliases: ["Smart TV", "pm_smart_televisions"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_smart_televisions
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Smart TV

Метод производства · `pm_smart_televisions` · `common/production_methods/ztr_new_production_methods.txt:6287`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_smart_televisions.dds`
- **unlocking_technologies**: [[tr/Технологии/Smart Appliances|Smart Appliances]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-glass-add|goods_input_glass_add]] = `5` → [[vanilla/Товары/Стекло|Стекло]]
    - `goods_input_manzoni_prints_add` = `40` → [[tr/Товары/Media Content|Media Content]]
    - `goods_input_plastics_add` = `5` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_telecommunications_add` = `35` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_processors_add` = `5` → [[tr/Товары/Processors|Processors]]
    - `goods_input_softwares_add` = `5` → [[tr/Товары/Software|Software]]
    - `goods_output_homeappliances_add` = `-25` → [[tr/Товары/Home Appliances|Home Appliances]]
    - `goods_output_televisions_add` = `75` → [[tr/Товары/Televisions|Televisions]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Television Category|Television Category]]

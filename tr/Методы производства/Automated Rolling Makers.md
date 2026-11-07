---
type: concept
description: "Метод производства «Automated Rolling Makers» — T&R 1.13, `pm_automated_cigarette_makers`"
project: vic3
audience: agent
source: tr
aliases: ["Automated Rolling Makers", "pm_automated_cigarette_makers"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_automated_cigarette_makers
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Automated Rolling Makers

Метод производства · `pm_automated_cigarette_makers` · `common/production_methods/ztr_agriculture_production_methods.txt:590`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_automated_cigarette_makers.dds`
- **unlocking_technologies**: [[tr/Технологии/Automated Industrial Robots|Automated Industrial Robots]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `10` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `3` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_robotics_add` = `1` → [[tr/Товары/Robotics|Robotics]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-tobacco-add|goods_output_tobacco_add]] = `35` → [[vanilla/Товары/Табак|Табак]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Промышленное производство|Промышленное производство]]

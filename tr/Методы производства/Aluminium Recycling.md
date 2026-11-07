---
type: concept
description: "Метод производства «Aluminium Recycling» — T&R 1.13, `pm_aluminium_recycling`"
project: vic3
audience: agent
source: tr
aliases: ["Aluminium Recycling", "pm_aluminium_recycling"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_aluminium_recycling
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Aluminium Recycling

Метод производства · `pm_aluminium_recycling` · `common/production_methods/ztr_new_production_methods.txt:9237`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/aluminium_recycling.dds`
- **unlocking_technologies**: [[tr/Технологии/Advanced Electric Arc Processes|Advanced Electric Arc Processes]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `1` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_output_aluminium_add` = `3` → [[tr/Товары/Aluminium|Aluminium]]
- **disallowing_laws**: [[tr/Законы/No Enviroment Protection|No Enviroment Protection]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Recycling Center|Recycling Center]]

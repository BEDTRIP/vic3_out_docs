---
type: concept
description: "Метод производства «Transistor Radios» — T&R 1.13, `pm_transistor_radios`"
project: vic3
audience: agent
source: tr
aliases: ["Transistor Radios", "pm_transistor_radios"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_transistor_radios
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Transistor Radios

Метод производства · `pm_transistor_radios` · `common/production_methods/ztr_new_production_methods.txt:3828`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_transistor_radios.dds`
- **unlocking_technologies**: [[tr/Технологии/Proto-Digital Devices|Proto-Digital Devices]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_manzoni_prints_add` = `7` → [[tr/Товары/Media Content|Media Content]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `15` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_telecommunications_add` = `25` → [[tr/Товары/Telecommunications|Telecommunications]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-telephones-add|goods_output_telephones_add]] = `-40` → [[vanilla/Товары/Телефоны|Телефоны]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-radios-add|goods_output_radios_add]] = `75` → [[vanilla/Товары/Радио|Радио]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Радио|Радио]]

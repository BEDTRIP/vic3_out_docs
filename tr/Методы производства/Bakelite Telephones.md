---
type: concept
description: "Метод производства «Bakelite Telephones» — T&R 1.13, `pm_bakelite_telephones`"
project: vic3
audience: agent
source: tr
aliases: ["Bakelite Telephones", "pm_bakelite_telephones"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_bakelite_telephones
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Bakelite Telephones

Метод производства · `pm_bakelite_telephones` · `common/production_methods/ztr_new_production_methods.txt:3906`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_bakelite_telephones.dds`
- **unlocking_technologies**: [[tr/Технологии/Ethylene|Ethylene]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `15` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `5` → [[vanilla/Товары/Инструменты|Инструменты]]
    - `goods_input_electroniccomponents_add` = `10` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-lead-add|goods_input_lead_add]] = `15` → [[vanilla/Товары/Свинец|Свинец]]
    - `goods_input_telecommunications_add` = `15` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_plastics_add` = `15` → [[tr/Товары/Пластмассы|Пластмассы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-telephones-add|goods_output_telephones_add]] = `80` → [[vanilla/Товары/Телефоны|Телефоны]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Телефоны|Телефоны]]

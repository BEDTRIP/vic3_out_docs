---
type: concept
description: "Метод производства «Smartphones» — T&R 1.13, `pm_smartphones`"
project: vic3
audience: agent
source: tr
aliases: ["Smartphones", "pm_smartphones"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_smartphones
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Smartphones

Метод производства · `pm_smartphones` · `common/production_methods/ztr_new_production_methods.txt:3986`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_smartphone.dds`
- **unlocking_technologies**: [[tr/Технологии/Smartphones|Smartphones]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `30` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_processors_add` = `15` → [[tr/Товары/Processors|Processors]]
    - `goods_input_batteries_add` = `20` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_softwares_add` = `10` → [[tr/Товары/Software|Software]]
    - `goods_input_telecommunications_add` = `30` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-telephones-add|goods_output_telephones_add]] = `155` → [[vanilla/Товары/Телефоны|Телефоны]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-academics-add|building_employment_academics_add]] = `500` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1000` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Телефоны|Телефоны]]

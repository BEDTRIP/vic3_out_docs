---
type: concept
description: "Метод производства «Electric Vehicles» — T&R 1.13, `pm_electric_vehicles_production`"
project: vic3
audience: agent
source: tr
aliases: ["Electric Vehicles", "pm_electric_vehicles_production"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_electric_vehicles_production
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Electric Vehicles

Метод производства · `pm_electric_vehicles_production` · `common/production_methods/ztr_new_production_methods.txt:2336`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_electric_vehicles_production.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[tr/Технологии/Electric Vehicles|Electric Vehicles]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_softwares_add` = `5` → [[tr/Товары/Software|Software]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `30` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-rubber-add|goods_input_rubber_add]] = `5` → [[vanilla/Товары/Каучук|Каучук]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `20` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_processors_add` = `10` → [[tr/Товары/Processors|Processors]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-dye-add|goods_input_dye_add]] = `5` → [[vanilla/Товары/Красители|Красители]]
    - `goods_input_aluminium_add` = `25` → [[tr/Товары/Aluminium|Aluminium]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-automobiles-add|goods_output_automobiles_add]] = `90` → [[tr/Товары/Автомобили|Автомобили]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `250` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1500` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1500` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Производство автомобилей|Производство автомобилей]]

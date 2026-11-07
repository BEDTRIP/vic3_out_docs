---
type: concept
description: "Метод производства «Gericke Systems» — T&R 1.13, `pm_hydroponic_gericke_system`"
project: vic3
source: tr
aliases: ["Gericke Systems", "pm_hydroponic_gericke_system"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_hydroponic_gericke_system
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Gericke Systems

Метод производства · `pm_hydroponic_gericke_system` · `common/production_methods/ztr_new_production_methods.txt:6595`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_hydroponic_gericke_system.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `5` → [[vanilla/Товары/Сталь|Сталь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `3` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `5` → [[vanilla/Товары/Удобрение|Удобрение]]
    - `goods_input_water_add` = `2` → [[tr/Товары/Water|Water]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `3750` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `750` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `500` → [[vanilla/Население/Типы/Механики|Механики]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Hydroponic Equipment|Hydroponic Equipment]]

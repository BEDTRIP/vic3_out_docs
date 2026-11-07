---
type: concept
description: "Метод производства «Synthetic Pesticides (pm_synthetic_pesticides)» — T&R 1.13, `pm_synthetic_pesticides`"
project: vic3
source: tr
aliases: ["Synthetic Pesticides (pm_synthetic_pesticides)", "Synthetic Pesticides", "pm_synthetic_pesticides"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_synthetic_pesticides
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Synthetic Pesticides (pm_synthetic_pesticides)

Метод производства · `pm_synthetic_pesticides` · `common/production_methods/ztr_agriculture_production_methods.txt:88`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_synthetic_pesticides.dds`
- **unlocking_technologies**: [[tr/Технологии/Synthetic Pesticides|Synthetic Pesticides]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fertilizer-add|goods_input_fertilizer_add]] = `20` → [[vanilla/Товары/Удобрение|Удобрение]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `3` → [[vanilla/Товары/ГСМ|ГСМ]]
    - `goods_input_pharmaceuticals_add` = `1` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-add|goods_output_grain_add]] = `90` → [[vanilla/Товары/Зерно|Зерно]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `2000` → [[vanilla/Население/Типы/Фермеры|Фермеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_maize_farm)|Основа (pmg_base_building_maize_farm)]], [[tr/Группы методов/Основа (pmg_base_building_millet_farm)|Основа (pmg_base_building_millet_farm)]], [[tr/Группы методов/Основа (pmg_base_building_rye_farm)|Основа (pmg_base_building_rye_farm)]], [[tr/Группы методов/Основа (pmg_base_building_wheat_farm)|Основа (pmg_base_building_wheat_farm)]]

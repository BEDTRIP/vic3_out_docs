---
type: concept
description: "Метод производства «Continuous Beet Diffusion» — T&R 1.13, `pm_continuous_diffusion_sugar_beet_refining`"
project: vic3
audience: agent
source: tr
aliases: ["Continuous Beet Diffusion", "pm_continuous_diffusion_sugar_beet_refining"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_continuous_diffusion_sugar_beet_refining
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_agriculture_production_methods.txt]
---
# Continuous Beet Diffusion

Метод производства · `pm_continuous_diffusion_sugar_beet_refining` · `common/production_methods/ztr_agriculture_production_methods.txt:1009`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_continuous_diffusion_sugar_refining.dds`
- **unlocking_technologies**: [[tr/Технологии/Controlled Environment Agriculture|Controlled Environment Agriculture]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-add|goods_output_grain_add]] = `-10` → [[vanilla/Товары/Зерно|Зерно]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `1` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_water_add` = `1` → [[tr/Товары/Water|Water]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-electricity-add|goods_input_electricity_add]] = `4` → [[vanilla/Товары/Электричество|Электричество]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-sugar-add|goods_output_sugar_add]] = `20` → [[vanilla/Товары/Сахар|Сахар]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Вторичный (pmg_secondary_building_rye_farm)|Вторичный (pmg_secondary_building_rye_farm)]], [[tr/Группы методов/Вторичный (pmg_secondary_building_wheat_farm)|Вторичный (pmg_secondary_building_wheat_farm)]]

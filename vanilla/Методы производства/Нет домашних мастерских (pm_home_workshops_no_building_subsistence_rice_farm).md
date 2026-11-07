---
type: concept
description: "Метод производства «Нет домашних мастерских (pm_home_workshops_no_building_subsistence_rice_farm)» — ваниль 1.13, `pm_home_workshops_no_building_subsistence_rice_farm`"
project: vic3
audience: agent
source: vanilla
aliases: ["Нет домашних мастерских (pm_home_workshops_no_building_subsistence_rice_farm)", "Нет домашних мастерских", "pm_home_workshops_no_building_subsistence_rice_farm"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_home_workshops_no_building_subsistence_rice_farm
paths: [.vanillaVIC3/common/production_methods/12_subsistence.txt]
---
# Нет домашних мастерских (pm_home_workshops_no_building_subsistence_rice_farm)

Метод производства · `pm_home_workshops_no_building_subsistence_rice_farm` · `common/production_methods/12_subsistence.txt:356`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/no_home_workshops.dds`
- **unlocking_laws**: [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-add|goods_output_grain_add]] = `1` → [[vanilla/Товары/Зерно|Зерно]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fabric-add|goods_output_fabric_add]] = `0.5` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-wood-add|goods_output_wood_add]] = `0.5` → [[vanilla/Товары/Древесина|Древесина]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Домашние мастерские (pmg_home_workshops_building_subsistence_rice_farm)|Домашние мастерские (pmg_home_workshops_building_subsistence_rice_farm)]]

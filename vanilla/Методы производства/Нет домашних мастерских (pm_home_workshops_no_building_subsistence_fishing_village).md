---
type: concept
description: "Метод производства «Нет домашних мастерских (pm_home_workshops_no_building_subsistence_fishing_village)» — ваниль 1.13, `pm_home_workshops_no_building_subsistence_fishing_village`"
project: vic3
audience: agent
source: vanilla
aliases: ["Нет домашних мастерских (pm_home_workshops_no_building_subsistence_fishing_village)", "Нет домашних мастерских", "pm_home_workshops_no_building_subsistence_fishing_village"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_home_workshops_no_building_subsistence_fishing_village
paths: [.vanillaVIC3/common/production_methods/12_subsistence.txt]
---
# Нет домашних мастерских (pm_home_workshops_no_building_subsistence_fishing_village)

Метод производства · `pm_home_workshops_no_building_subsistence_fishing_village` · `common/production_methods/12_subsistence.txt:293`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/no_home_workshops.dds`
- **unlocking_laws**: [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fish-add|goods_output_fish_add]] = `0.5` → [[vanilla/Товары/Рыба|Рыба]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fabric-add|goods_output_fabric_add]] = `0.25` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-wood-add|goods_output_wood_add]] = `0.25` → [[vanilla/Товары/Древесина|Древесина]]

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Домашние мастерские (pmg_home_workshops_building_subsistence_fishing_village)|Домашние мастерские (pmg_home_workshops_building_subsistence_fishing_village)]]

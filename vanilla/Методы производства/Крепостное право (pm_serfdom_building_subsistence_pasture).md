---
type: concept
description: "Метод производства «Крепостное право (pm_serfdom_building_subsistence_pasture)» — ваниль 1.15, `pm_serfdom_building_subsistence_pasture`"
project: vic3
audience: agent
source: vanilla
aliases: ["Крепостное право (pm_serfdom_building_subsistence_pasture)", "Крепостное право", "pm_serfdom_building_subsistence_pasture"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_serfdom_building_subsistence_pasture
paths: [.vanillaVIC3/common/production_methods/12_subsistence.txt]
---
# Крепостное право (pm_serfdom_building_subsistence_pasture)

Метод производства · `pm_serfdom_building_subsistence_pasture` · `common/production_methods/12_subsistence.txt:259`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/serfdom.dds`
- **unlocking_laws**: [[vanilla/Законы/Крепостное право|Крепостное право]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-meat-add|goods_output_meat_add]] = `0.33` → [[vanilla/Товары/Мясо|Мясо]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-subsistence-output-add|building_subsistence_output_add]] = `3`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Крепостное право (pmg_serfdom_building_subsistence_pasture)|Крепостное право (pmg_serfdom_building_subsistence_pasture)]]

---
type: concept
description: "Метод производства «Крепостное право (pm_serfdom)» — ваниль 1.15, `pm_serfdom`"
project: vic3
audience: agent
source: vanilla
aliases: ["Крепостное право (pm_serfdom)", "Serfdom", "pm_serfdom"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_serfdom
paths: [.vanillaVIC3/common/production_methods/12_subsistence.txt]
---
# Крепостное право (pm_serfdom)

Метод производства · `pm_serfdom` · `common/production_methods/12_subsistence.txt:132`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/serfdom.dds`
- **unlocking_laws**: [[vanilla/Законы/Крепостное право|Крепостное право]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-grain-add|goods_output_grain_add]] = `0.5` → [[vanilla/Товары/Зерно|Зерно]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-subsistence-output-add|building_subsistence_output_add]] = `3`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Крепостное право (pmg_serfdom_building_subsistence_farm)|Крепостное право (pmg_serfdom_building_subsistence_farm)]]

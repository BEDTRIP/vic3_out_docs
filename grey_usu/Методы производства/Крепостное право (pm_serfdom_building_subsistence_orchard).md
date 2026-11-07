---
type: concept
description: "Метод производства «Крепостное право (pm_serfdom_building_subsistence_orchard)» — grey USU 1.13, `pm_serfdom_building_subsistence_orchard`"
project: vic3
source: grey_usu
aliases: ["Крепостное право (pm_serfdom_building_subsistence_orchard)", "Крепостное право", "pm_serfdom_building_subsistence_orchard"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_serfdom_building_subsistence_orchard
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_road_carts_subsistence.txt]
replaces: "[[vanilla/Методы производства/Крепостное право (pm_serfdom_building_subsistence_orchard)]]"
---
# Крепостное право (pm_serfdom_building_subsistence_orchard)

Метод производства · `pm_serfdom_building_subsistence_orchard` · `common/production_methods/yMoG_USU_road_carts_subsistence.txt:281`

## Отличия от ваниль

- **state_modifiers**: добавлено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/serfdom.dds`
- **unlocking_laws**: [[vanilla/Законы/Крепостное право|Крепостное право]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_fruit_add` = `0.33` → [[vanilla/Товары/Фрукты|Фрукты]]
  - **unscaled**:
    - `building_subsistence_output_add` = `3`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_tax_capacity_add` = `0.8`

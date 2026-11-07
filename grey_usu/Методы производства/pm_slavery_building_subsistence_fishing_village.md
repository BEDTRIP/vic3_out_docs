---
type: concept
description: "Метод производства «pm_slavery_building_subsistence_fishing_village» — grey USU 1.13, `pm_slavery_building_subsistence_fishing_village`"
project: vic3
audience: agent
source: grey_usu
aliases: ["pm_slavery_building_subsistence_fishing_village"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_slavery_building_subsistence_fishing_village
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_road_carts_subsistence.txt]
---
# pm_slavery_building_subsistence_fishing_village

Метод производства · `pm_slavery_building_subsistence_fishing_village` · `common/production_methods/yMoG_USU_road_carts_subsistence.txt:439`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/unused/slavery.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_laws**: [[grey_usu/Законы/law_forced_labour|law_forced_labour]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-fish-add|goods_output_fish_add]] = `0.5` → [[vanilla/Товары/Рыба|Рыба]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-subsistence-output-add|building_subsistence_output_add]] = `3`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-add|state_tax_capacity_add]] = `0.8`

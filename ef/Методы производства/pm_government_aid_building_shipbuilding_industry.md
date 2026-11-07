---
type: concept
description: "Метод производства «pm_government_aid_building_shipbuilding_industry» — E&F 1.13, `pm_government_aid_building_shipbuilding_industry`"
project: vic3
source: ef
aliases: ["pm_government_aid_building_shipbuilding_industry"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_government_aid_building_shipbuilding_industry
paths: [E&F/common/production_methods/00_ef_market_liquidity.txt]
---
# pm_government_aid_building_shipbuilding_industry

Метод производства · `pm_government_aid_building_shipbuilding_industry` · `common/production_methods/00_ef_market_liquidity.txt:206`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/government_run.dds`
- **pollution_generation**: `20`
- **unlocking_technologies**: [[vanilla/Технологии/Дуговая сварка|Дуговая сварка]], `pm_metal_shipbuilding`, `pm_arc_welding_shipbuilding`
- **unlocking_laws**: [[vanilla/Законы/Массовый призыв|Массовый призыв]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_war_bond_add` = `1`
    - [[vanilla/движок/Модификаторы G#^m-goods-output-steamers-add|goods_output_steamers_add]] = `80` → [[vanilla/Товары/Пароходы|Пароходы]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-ironclads-add|goods_output_ironclads_add]] = `25` → [[vanilla/Товары/Броненосцы|Броненосцы]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1500` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

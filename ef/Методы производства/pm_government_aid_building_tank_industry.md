---
type: concept
description: "Метод производства «pm_government_aid_building_tank_industry» — E&F 1.13, `pm_government_aid_building_tank_industry`"
project: vic3
source: ef
aliases: ["pm_government_aid_building_tank_industry"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_government_aid_building_tank_industry
paths: [E&F/common/production_methods/00_ef_market_liquidity.txt]
---
# pm_government_aid_building_tank_industry

Метод производства · `pm_government_aid_building_tank_industry` · `common/production_methods/00_ef_market_liquidity.txt:175`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/government_run.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Подвижная броня|Подвижная броня]]
- **unlocking_laws**: [[vanilla/Законы/Массовый призыв|Массовый призыв]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_war_bond_add` = `1`
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `-10` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-hardwood-add|goods_input_hardwood_add]] = `-20` → [[vanilla/Товары/Твёрдая древесина|Твёрдая древесина]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `-20` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-oil-add|goods_input_oil_add]] = `-20` → [[vanilla/Товары/ГСМ|ГСМ]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-tanks-add|goods_output_tanks_add]] = `40` → [[vanilla/Товары/Танки|Танки]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

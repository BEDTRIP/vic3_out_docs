---
type: concept
description: "Метод производства «pm_government_aid_building_arms_industry_1» — E&F 1.13, `pm_government_aid_building_arms_industry_1`"
project: vic3
audience: agent
source: ef
aliases: ["pm_government_aid_building_arms_industry_1"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_government_aid_building_arms_industry_1
paths: [E&F/common/production_methods/00_ef_market_liquidity.txt]
---
# pm_government_aid_building_arms_industry_1

Метод производства · `pm_government_aid_building_arms_industry_1` · `common/production_methods/00_ef_market_liquidity.txt:93`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/government_run.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Винтовка со скользящим затвором|Винтовка со скользящим затвором]]
- **unlocking_laws**: [[vanilla/Законы/Массовый призыв|Массовый призыв]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_war_bond_add` = `1`
    - [[vanilla/движок/Модификаторы G#^m-goods-output-small-arms-add|goods_output_small_arms_add]] = `75` → [[vanilla/Товары/Стрелковое оружие|Стрелковое оружие]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `1000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `2000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `1500` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Методы производства** (unlocking_production_methods): [[ef/Методы производства/Частная собственность (pm_privately_owned_building_arms_industry)|Частная собственность (pm_privately_owned_building_arms_industry)]]

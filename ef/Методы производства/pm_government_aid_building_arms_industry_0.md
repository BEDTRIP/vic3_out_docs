---
type: concept
description: "Метод производства «pm_government_aid_building_arms_industry_0» — E&F 1.13, `pm_government_aid_building_arms_industry_0`"
project: vic3
source: ef
aliases: ["pm_government_aid_building_arms_industry_0"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_government_aid_building_arms_industry_0
paths: [E&F/common/production_methods/00_ef_market_liquidity.txt]
---
# pm_government_aid_building_arms_industry_0

Метод производства · `pm_government_aid_building_arms_industry_0` · `common/production_methods/00_ef_market_liquidity.txt:67`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/government_run.dds`
- **unlocking_technologies**: [[vanilla/Технологии/Казнозарядная артиллерия|Казнозарядная артиллерия]]
- **unlocking_laws**: [[vanilla/Законы/Массовый призыв|Массовый призыв]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_war_bond_add` = `1`
    - `goods_output_artillery_add` = `40` → [[vanilla/Товары/Артиллерия|Артиллерия]]
  - **level_scaled**:
    - `building_employment_machinists_add` = `500` → [[vanilla/Население/Типы/Механики|Механики]]
    - `building_employment_engineers_add` = `500` → [[vanilla/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Методы производства** (unlocking_production_methods): [[ef/Методы производства/Частная собственность (pm_privately_owned_building_arms_industry)|Частная собственность (pm_privately_owned_building_arms_industry)]]

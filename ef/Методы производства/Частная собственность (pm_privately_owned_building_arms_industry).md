---
type: concept
description: "Метод производства «Частная собственность (pm_privately_owned_building_arms_industry)» — E&F 1.13, `pm_privately_owned_building_arms_industry`"
project: vic3
source: ef
aliases: ["Частная собственность (pm_privately_owned_building_arms_industry)", "Частная собственность", "pm_privately_owned_building_arms_industry"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_privately_owned_building_arms_industry
paths: [E&F/common/production_methods/00_ef_market_liquidity.txt]
---
# Частная собственность (pm_privately_owned_building_arms_industry)

Метод производства · `pm_privately_owned_building_arms_industry` · `common/production_methods/00_ef_market_liquidity.txt:150`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **unlocking_production_methods**: [[vanilla/Методы производства/Винтовки|Винтовки]], [[vanilla/Методы производства/Магазинные винтовки|Магазинные винтовки]], [[vanilla/Методы производства/Винтовки со скользящим затвором|Винтовки со скользящим затвором]], [[ef/Методы производства/pm_government_aid_building_arms_industry_1|pm_government_aid_building_arms_industry_1]], [[ef/Методы производства/pm_government_aid_building_arms_industry_0|pm_government_aid_building_arms_industry_0]]
- **disallowing_laws**: [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Советская республика|Советская республика]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `100` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
  - **unscaled**:
    - `building_capitalists_money_add` = `5`

---
type: concept
description: "Метод производства «Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)» — ваниль 1.13, `pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture`"
project: vic3
audience: agent
source: vanilla
aliases: ["Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)", "Частная собственность", "pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture
paths: [.vanillaVIC3/common/production_methods/14_companies.txt]
---
# Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)

Метод производства · `pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture` · `common/production_methods/14_companies.txt:52`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `aristocrat_owned`
- **unlocking_laws**: [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]]
- **disallowing_laws**: [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Кооперативное владение|Кооперативное владение]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `15` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-aristocrats-add|building_employment_aristocrats_add]] = `10` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `25` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-capitalists-shares-add|building_capitalists_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-aristocrats-shares-add|building_aristocrats_shares_add]] = `10`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Собственность (pmg_ownership_building_company_headquarter)|Собственность (pmg_ownership_building_company_headquarter)]]

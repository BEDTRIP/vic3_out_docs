---
type: concept
description: "Метод производства «Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_bureaucrats)» — ваниль 1.15, `pm_company_headquarter_principle_divine_economics_2_bureaucrats`"
project: vic3
audience: agent
source: vanilla
aliases: ["Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_bureaucrats)", "Увеличенный надзор духовенства", "pm_company_headquarter_principle_divine_economics_2_bureaucrats"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_principle_divine_economics_2_bureaucrats
paths: [.vanillaVIC3/common/production_methods/14_companies.txt]
---
# Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_bureaucrats)

Метод производства · `pm_company_headquarter_principle_divine_economics_2_bureaucrats` · `common/production_methods/14_companies.txt:296`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `bureaucrat_owned`
- **disallowing_laws**: [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Кооперативное владение|Кооперативное владение]]
- **unlocking_principles**: `principle_divine_economics_2`, `principle_divine_economics_3`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `10` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `15` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clergymen-add|building_employment_clergymen_add]] = `25` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-capitalists-shares-add|building_capitalists_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-bureaucrats-shares-add|building_bureaucrats_shares_add]] = `5`
    - [[vanilla/движок/Модификаторы B#^m-building-clergymen-shares-add|building_clergymen_shares_add]] = `2`
    - [[vanilla/движок/Модификаторы B#^m-building-company-government-dividends-add|building_company_government_dividends_add]] = `0.25`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Собственность (pmg_ownership_building_company_headquarter)|Собственность (pmg_ownership_building_company_headquarter)]]

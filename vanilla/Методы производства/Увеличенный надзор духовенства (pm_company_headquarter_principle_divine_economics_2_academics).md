---
type: concept
description: "Метод производства «Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_academics)» — ваниль 1.13, `pm_company_headquarter_principle_divine_economics_2_academics`"
project: vic3
source: vanilla
aliases: ["Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_academics)", "Увеличенный надзор духовенства", "pm_company_headquarter_principle_divine_economics_2_academics"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_principle_divine_economics_2_academics
paths: [.vanillaVIC3/common/production_methods/14_companies.txt]
---
# Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_academics)

Метод производства · `pm_company_headquarter_principle_divine_economics_2_academics` · `common/production_methods/14_companies.txt:329`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `academic_owned`
- **disallowing_laws**: [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Кооперативное владение|Кооперативное владение]]
- **unlocking_principles**: `principle_divine_economics_2`, `principle_divine_economics_3`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `10` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_academics_add` = `15` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_clergymen_add` = `25` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_academics_shares_add` = `5`
    - `building_clergymen_shares_add` = `2`
    - `building_company_worker_dividends_add` = `0.25`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Собственность (pmg_ownership_building_company_headquarter)|Собственность (pmg_ownership_building_company_headquarter)]]

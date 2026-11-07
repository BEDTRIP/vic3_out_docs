---
type: concept
description: "Метод производства «Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_shopkeepers)» — grey USU 1.13, `pm_company_headquarter_principle_divine_economics_2_shopkeepers`"
project: vic3
source: grey_usu
aliases: ["Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_shopkeepers)", "Увеличенный надзор духовенства", "pm_company_headquarter_principle_divine_economics_2_shopkeepers"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_principle_divine_economics_2_shopkeepers
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_owners_tax_pms.txt]
replaces: "[[vanilla/Методы производства/Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_shopkeepers)]]"
---
# Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_shopkeepers)

Метод производства · `pm_company_headquarter_principle_divine_economics_2_shopkeepers` · `common/production_methods/yMoG_USU_owners_tax_pms.txt:467`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `shopkeeper_owned`
- **disallowing_laws**: [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Кооперативное владение|Кооперативное владение]]
- **unlocking_principles**: `principle_divine_economics_2`, `principle_divine_economics_3`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `10` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_shopkeepers_add` = `20` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clergymen_add` = `10` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
    - `building_employment_clerks_add` = `10` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_shopkeepers_shares_add` = `3`
    - `building_clergymen_shares_add` = `3`
    - `building_company_worker_dividends_add` = `0.35`

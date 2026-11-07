---
type: concept
description: "Метод производства «Частная собственность (pm_company_headquarter_privately_owned_academics)» — grey USU 1.13, `pm_company_headquarter_privately_owned_academics`"
project: vic3
source: grey_usu
aliases: ["Частная собственность (pm_company_headquarter_privately_owned_academics)", "Частная собственность", "pm_company_headquarter_privately_owned_academics"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_privately_owned_academics
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_owners_tax_pms.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_company_headquarter_privately_owned_academics)]]"
---
# Частная собственность (pm_company_headquarter_privately_owned_academics)

Метод производства · `pm_company_headquarter_privately_owned_academics` · `common/production_methods/yMoG_USU_owners_tax_pms.txt:336`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `academic_owned`
- **disallowing_laws**: [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Кооперативное владение|Кооперативное владение]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `10` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_academics_add` = `30` → [[vanilla/Население/Типы/Учёные|Учёные]]
    - `building_employment_clerks_add` = `10` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_academics_shares_add` = `3`
    - `building_company_worker_dividends_add` = `0.35`

---
type: concept
description: "Метод производства «Частная собственность (pm_company_headquarter_privately_owned)» — grey USU 1.13, `pm_company_headquarter_privately_owned`"
project: vic3
source: grey_usu
aliases: ["Частная собственность (pm_company_headquarter_privately_owned)", "Частная собственность", "pm_company_headquarter_privately_owned"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_privately_owned
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_owners_tax_pms.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_company_headquarter_privately_owned)]]"
---
# Частная собственность (pm_company_headquarter_privately_owned)

Метод производства · `pm_company_headquarter_privately_owned` · `common/production_methods/yMoG_USU_owners_tax_pms.txt:189`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `capitalist_owned`
- **disallowing_laws**: [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Кооперативное владение|Кооперативное владение]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `25` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_shopkeepers_add` = `15` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clerks_add` = `10` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_shopkeepers_shares_add` = `1`

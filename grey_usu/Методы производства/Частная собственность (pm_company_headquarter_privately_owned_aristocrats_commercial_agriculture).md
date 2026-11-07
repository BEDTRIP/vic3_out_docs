---
type: concept
description: "Метод производства «Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)» — grey USU 1.13, `pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture`"
project: vic3
source: grey_usu
aliases: ["Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)", "Частная собственность", "pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_owners_tax_pms.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)]]"
---
# Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)

Метод производства · `pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture` · `common/production_methods/yMoG_USU_owners_tax_pms.txt:245`

## Отличия от ваниль

- **disallowing_laws**: изменено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `aristocrat_owned`
- **unlocking_laws**: [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]]
- **disallowing_laws**: [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Кооперативное владение|Кооперативное владение]], [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `15` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_aristocrats_add` = `10` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - `building_employment_shopkeepers_add` = `15` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clerks_add` = `10` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_aristocrats_shares_add` = `10`
    - `building_shopkeepers_shares_add` = `1`

---
type: concept
description: "Метод производства «Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_aristocrats_commercial_agriculture)» — grey USU 1.13, `pm_company_headquarter_principle_divine_economics_2_aristocrats_commercial_agriculture`"
project: vic3
source: grey_usu
aliases: ["Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_aristocrats_commercial_agriculture)", "Увеличенный надзор духовенства", "pm_company_headquarter_principle_divine_economics_2_aristocrats_commercial_agriculture"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_principle_divine_economics_2_aristocrats_commercial_agriculture
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_owners_tax_pms.txt]
replaces: "[[vanilla/Методы производства/Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_aristocrats_commercial_agriculture)]]"
---
# Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_aristocrats_commercial_agriculture)

Метод производства · `pm_company_headquarter_principle_divine_economics_2_aristocrats_commercial_agriculture` · `common/production_methods/yMoG_USU_owners_tax_pms.txt:429`

## Отличия от ваниль

- **disallowing_laws**: изменено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `aristocrat_owned`
- **unlocking_laws**: [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]]
- **disallowing_laws**: [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Кооперативное владение|Кооперативное владение]], [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]]
- **unlocking_principles**: `principle_divine_economics_2`, `principle_divine_economics_3`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `12` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-aristocrats-add|building_employment_aristocrats_add]] = `8` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clergymen-add|building_employment_clergymen_add]] = `20` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `10` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-capitalists-shares-add|building_capitalists_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-aristocrats-shares-add|building_aristocrats_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-clergymen-shares-add|building_clergymen_shares_add]] = `2`

---
type: concept
description: "Метод производства «Частная собственность (pm_financial_district_privately_owned)» — grey USU 1.13, `pm_financial_district_privately_owned`"
project: vic3
source: grey_usu
aliases: ["Частная собственность (pm_financial_district_privately_owned)", "Частная собственность", "pm_financial_district_privately_owned"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_financial_district_privately_owned
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_owners_tax_pms.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_financial_district_privately_owned)]]"
---
# Частная собственность (pm_financial_district_privately_owned)

Метод производства · `pm_financial_district_privately_owned` · `common/production_methods/yMoG_USU_owners_tax_pms.txt:130`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **replacement_if_valid**: [[grey_usu/Методы производства/Увеличенный надзор духовенства (pm_financial_district_principle_divine_economics_2)|Увеличенный надзор духовенства (pm_financial_district_principle_divine_economics_2)]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `25` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `15` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `10` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-capitalists-shares-add|building_capitalists_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-shopkeepers-shares-add|building_shopkeepers_shares_add]] = `1`

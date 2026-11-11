---
type: concept
description: "Метод производства «Частная собственность (pm_financial_district_privately_owned)» — ваниль 1.15, `pm_financial_district_privately_owned`"
project: vic3
audience: agent
source: vanilla
aliases: ["Частная собственность (pm_financial_district_privately_owned)", "Частная собственность", "pm_financial_district_privately_owned"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_financial_district_privately_owned
paths: [.vanillaVIC3/common/production_methods/11_private_infrastructure.txt]
---
# Частная собственность (pm_financial_district_privately_owned)

Метод производства · `pm_financial_district_privately_owned` · `common/production_methods/11_private_infrastructure.txt:454`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **replacement_if_valid**: [[vanilla/Методы производства/Увеличенный надзор духовенства (pm_financial_district_principle_divine_economics_2)|Увеличенный надзор духовенства (pm_financial_district_principle_divine_economics_2)]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `50` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `25` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `25` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-capitalists-shares-add|building_capitalists_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-shopkeepers-shares-add|building_shopkeepers_shares_add]] = `1`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Собственность (pmg_ownership_building_financial_district)|Собственность (pmg_ownership_building_financial_district)]]

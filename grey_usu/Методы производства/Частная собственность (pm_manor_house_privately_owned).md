---
type: concept
description: "Метод производства «Частная собственность (pm_manor_house_privately_owned)» — grey USU 1.13, `pm_manor_house_privately_owned`"
project: vic3
audience: agent
source: grey_usu
aliases: ["Частная собственность (pm_manor_house_privately_owned)", "Частная собственность", "pm_manor_house_privately_owned"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_manor_house_privately_owned
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_owners_tax_pms.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_manor_house_privately_owned)]]"
---
# Частная собственность (pm_manor_house_privately_owned)

Метод производства · `pm_manor_house_privately_owned` · `common/production_methods/yMoG_USU_owners_tax_pms.txt:44`

## Отличия от ваниль

- **state_modifiers**: добавлено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/ownership_aristocrats.dds`
- **replacement_if_valid**: [[grey_usu/Методы производства/Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)|Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-add|state_tax_capacity_add]] = `-1`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-aristocrats-add|building_employment_aristocrats_add]] = `30` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-aristocrats-shares-add|building_aristocrats_shares_add]] = `10`

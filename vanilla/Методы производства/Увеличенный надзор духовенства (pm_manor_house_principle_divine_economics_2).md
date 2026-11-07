---
type: concept
description: "Метод производства «Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)» — ваниль 1.13, `pm_manor_house_principle_divine_economics_2`"
project: vic3
source: vanilla
aliases: ["Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)", "Increased Clergy Oversight", "pm_manor_house_principle_divine_economics_2"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_manor_house_principle_divine_economics_2
paths: [.vanillaVIC3/common/production_methods/11_private_infrastructure.txt]
---
# Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)

Метод производства · `pm_manor_house_principle_divine_economics_2` · `common/production_methods/11_private_infrastructure.txt:524`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_principles**: `principle_divine_economics_2`, `principle_divine_economics_3`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-aristocrats-add|building_employment_aristocrats_add]] = `50` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clergymen-add|building_employment_clergymen_add]] = `50` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-aristocrats-shares-add|building_aristocrats_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-clergymen-shares-add|building_clergymen_shares_add]] = `1`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Собственность (pmg_ownership_building_manor_house)|Собственность (pmg_ownership_building_manor_house)]]
- **Методы производства** (replacement_if_valid): [[vanilla/Методы производства/Частная собственность (pm_manor_house_privately_owned)|Частная собственность (pm_manor_house_privately_owned)]]

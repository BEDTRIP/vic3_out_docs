---
type: concept
description: "Метод производства «Частная собственность (pm_manor_house_privately_owned)» — ваниль 1.15, `pm_manor_house_privately_owned`"
project: vic3
audience: agent
source: vanilla
aliases: ["Частная собственность (pm_manor_house_privately_owned)", "Частная собственность", "pm_manor_house_privately_owned"]
tags: [ваниль, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_manor_house_privately_owned
paths: [.vanillaVIC3/common/production_methods/11_private_infrastructure.txt]
---
# Частная собственность (pm_manor_house_privately_owned)

Метод производства · `pm_manor_house_privately_owned` · `common/production_methods/11_private_infrastructure.txt:510`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/ownership_aristocrats.dds`
- **replacement_if_valid**: [[vanilla/Методы производства/Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)|Увеличенный надзор духовенства (pm_manor_house_principle_divine_economics_2)]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-aristocrats-add|building_employment_aristocrats_add]] = `50` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-aristocrats-shares-add|building_aristocrats_shares_add]] = `10`

## Ссылаются

- **Группы методов** (методы группы): [[vanilla/Группы методов/Собственность (pmg_ownership_building_manor_house)|Собственность (pmg_ownership_building_manor_house)]]

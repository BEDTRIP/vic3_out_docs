---
type: concept
description: "Метод производства «Частная собственность (pm_company_headquarter_privately_owned_aristocrats)» — E&F 1.13, `pm_company_headquarter_privately_owned_aristocrats`"
project: vic3
audience: agent
source: ef
aliases: ["Частная собственность (pm_company_headquarter_privately_owned_aristocrats)", "Частная собственность", "pm_company_headquarter_privately_owned_aristocrats"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_privately_owned_aristocrats
paths: [E&F/common/production_methods/11_ef_private_infrastructure.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_company_headquarter_privately_owned_aristocrats)]]"
---
# Частная собственность (pm_company_headquarter_privately_owned_aristocrats)

Метод производства · `pm_company_headquarter_privately_owned_aristocrats` · `common/production_methods/11_ef_private_infrastructure.txt:75` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_modifiers**: изменено
- **texture**: убрано
- **is_hidden_when_unavailable**: убрано
- **unlocking_company_categories**: убрано
- **disallowing_laws**: убрано

## Поля

- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `3` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-aristocrats-add|building_employment_aristocrats_add]] = `3.5` → [[vanilla/Население/Типы/Аристократы|Аристократы]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `3.5` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-capitalists-shares-add|building_capitalists_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-aristocrats-shares-add|building_aristocrats_shares_add]] = `10`

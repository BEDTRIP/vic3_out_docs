---
type: concept
description: "Метод производства «Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)» — E&F 1.13, `pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture`"
project: vic3
source: ef
aliases: ["Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)", "Частная собственность", "pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture
paths: [E&F/common/production_methods/11_ef_private_infrastructure.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)]]"
---
# Частная собственность (pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture)

Метод производства · `pm_company_headquarter_privately_owned_aristocrats_commercial_agriculture` · `common/production_methods/11_ef_private_infrastructure.txt:88` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_modifiers**: изменено
- **texture**: убрано
- **is_hidden_when_unavailable**: убрано
- **unlocking_company_categories**: убрано
- **unlocking_laws**: убрано
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

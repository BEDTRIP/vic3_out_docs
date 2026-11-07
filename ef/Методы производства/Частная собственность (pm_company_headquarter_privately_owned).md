---
type: concept
description: "Метод производства «Частная собственность (pm_company_headquarter_privately_owned)» — E&F 1.13, `pm_company_headquarter_privately_owned`"
project: vic3
source: ef
aliases: ["Частная собственность (pm_company_headquarter_privately_owned)", "Частная собственность", "pm_company_headquarter_privately_owned"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_privately_owned
paths: [E&F/common/production_methods/11_ef_private_infrastructure.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_company_headquarter_privately_owned)]]"
---
# Частная собственность (pm_company_headquarter_privately_owned)

Метод производства · `pm_company_headquarter_privately_owned` · `common/production_methods/11_ef_private_infrastructure.txt:62` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_modifiers**: изменено
- **texture**: убрано
- **is_hidden_when_unavailable**: убрано
- **unlocking_company_categories**: убрано
- **disallowing_laws**: убрано

## Поля

- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `3` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_shopkeepers_add` = `3.5` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clerks_add` = `3.5` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_shopkeepers_shares_add` = `1`

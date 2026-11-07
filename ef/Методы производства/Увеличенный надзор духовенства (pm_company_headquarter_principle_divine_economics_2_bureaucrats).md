---
type: concept
description: "Метод производства «Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_bureaucrats)» — E&F 1.13, `pm_company_headquarter_principle_divine_economics_2_bureaucrats`"
project: vic3
source: ef
aliases: ["Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_bureaucrats)", "Увеличенный надзор духовенства", "pm_company_headquarter_principle_divine_economics_2_bureaucrats"]
tags: [ef, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_principle_divine_economics_2_bureaucrats
paths: [E&F/common/production_methods/11_ef_private_infrastructure.txt]
replaces: "[[vanilla/Методы производства/Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_bureaucrats)]]"
---
# Увеличенный надзор духовенства (pm_company_headquarter_principle_divine_economics_2_bureaucrats)

Метод производства · `pm_company_headquarter_principle_divine_economics_2_bureaucrats` · `common/production_methods/11_ef_private_infrastructure.txt:198` · заменяет запись ваниль (`REPLACE:`)

## Отличия от ваниль

- **building_modifiers**: изменено
- **texture**: убрано
- **is_hidden_when_unavailable**: убрано
- **unlocking_company_categories**: убрано
- **disallowing_laws**: убрано
- **unlocking_principles**: убрано

## Поля

- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_capitalists_add` = `3` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - `building_employment_bureaucrats_add` = `3.5` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - `building_employment_clergymen_add` = `3.5` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
  - **unscaled**:
    - `building_capitalists_shares_add` = `10`
    - `building_bureaucrats_shares_add` = `5`
    - `building_clergymen_shares_add` = `2`
    - `building_company_government_dividends_add` = `0.25`

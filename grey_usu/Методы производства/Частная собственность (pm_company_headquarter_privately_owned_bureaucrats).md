---
type: concept
description: "Метод производства «Частная собственность (pm_company_headquarter_privately_owned_bureaucrats)» — grey USU 1.13, `pm_company_headquarter_privately_owned_bureaucrats`"
project: vic3
audience: agent
source: grey_usu
aliases: ["Частная собственность (pm_company_headquarter_privately_owned_bureaucrats)", "Частная собственность", "pm_company_headquarter_privately_owned_bureaucrats"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_privately_owned_bureaucrats
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_owners_tax_pms.txt]
replaces: "[[vanilla/Методы производства/Частная собственность (pm_company_headquarter_privately_owned_bureaucrats)]]"
---
# Частная собственность (pm_company_headquarter_privately_owned_bureaucrats)

Метод производства · `pm_company_headquarter_privately_owned_bureaucrats` · `common/production_methods/yMoG_USU_owners_tax_pms.txt:309`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `bureaucrat_owned`
- **disallowing_laws**: [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Кооперативное владение|Кооперативное владение]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-capitalists-add|building_employment_capitalists_add]] = `10` → [[vanilla/Население/Типы/Капиталисты|Капиталисты]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `30` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `10` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-capitalists-shares-add|building_capitalists_shares_add]] = `10`
    - [[vanilla/движок/Модификаторы B#^m-building-bureaucrats-shares-add|building_bureaucrats_shares_add]] = `3`
    - [[vanilla/движок/Модификаторы B#^m-building-company-worker-dividends-add|building_company_worker_dividends_add]] = `0.35`

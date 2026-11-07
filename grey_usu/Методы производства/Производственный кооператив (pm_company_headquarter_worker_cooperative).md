---
type: concept
description: "Метод производства «Производственный кооператив (pm_company_headquarter_worker_cooperative)» — grey USU 1.13, `pm_company_headquarter_worker_cooperative`"
project: vic3
source: grey_usu
aliases: ["Производственный кооператив (pm_company_headquarter_worker_cooperative)", "Производственный кооператив", "pm_company_headquarter_worker_cooperative"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_worker_cooperative
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_owners_tax_pms.txt]
replaces: "[[vanilla/Методы производства/Производственный кооператив]]"
---
# Производственный кооператив (pm_company_headquarter_worker_cooperative)

Метод производства · `pm_company_headquarter_worker_cooperative` · `common/production_methods/yMoG_USU_owners_tax_pms.txt:594`

## Отличия от ваниль

- **replacement_if_valid**: добавлено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/worker_cooperative.dds`
- **replacement_if_valid**: [[grey_usu/Методы производства/Производственный кооператив (pm_company_headquarter_coop_collective_agriculture)|Производственный кооператив (pm_company_headquarter_coop_collective_agriculture)]]
- **unlocking_laws**: [[vanilla/Законы/Кооперативное владение|Кооперативное владение]]
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_shopkeepers_add` = `30` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - `building_employment_clerks_add` = `20` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_shopkeepers_shares_add` = `94`
    - `building_clerks_shares_add` = `9`

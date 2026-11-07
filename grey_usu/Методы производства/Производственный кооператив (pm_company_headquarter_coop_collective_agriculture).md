---
type: concept
description: "Метод производства «Производственный кооператив (pm_company_headquarter_coop_collective_agriculture)» — grey USU 1.13, `pm_company_headquarter_coop_collective_agriculture`"
project: vic3
source: grey_usu
aliases: ["Производственный кооператив (pm_company_headquarter_coop_collective_agriculture)", "Производственный кооператив", "pm_company_headquarter_coop_collective_agriculture"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_coop_collective_agriculture
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_owners_tax_pms.txt]
---
# Производственный кооператив (pm_company_headquarter_coop_collective_agriculture)

Метод производства · `pm_company_headquarter_coop_collective_agriculture` · `common/production_methods/yMoG_USU_owners_tax_pms.txt:615`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/worker_cooperative.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_company_categories**: `aristocrat_owned`
- **unlocking_laws**: [[vanilla/Законы/Коллективизированное сельское хозяйство|Коллективизированное сельское хозяйство]]
- **disallowing_laws**: [[vanilla/Законы/Крепостное право|Крепостное право]], [[vanilla/Законы/Арендаторы|Арендаторы]], [[vanilla/Законы/Крестьянское хозяйство|Крестьянское хозяйство]], [[vanilla/Законы/Коммерческое сельское хозяйство|Коммерческое сельское хозяйство]], [[vanilla/Законы/Аграрность|Аграрность]], [[vanilla/Законы/Запрет промышленности|Запрет промышленности]], [[vanilla/Законы/Традиционализм|Традиционализм]], [[vanilla/Законы/Интервенционизм|Интервенционизм]], [[vanilla/Законы/Свободная конкуренция|Свободная конкуренция]], [[vanilla/Законы/Командная экономика|Командная экономика]], [[vanilla/Законы/Добывающая экономика|Добывающая экономика]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `15` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-farmers-add|building_employment_farmers_add]] = `15` → [[vanilla/Население/Типы/Фермеры|Фермеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `20` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-shopkeepers-shares-add|building_shopkeepers_shares_add]] = `94`
    - [[vanilla/движок/Модификаторы B#^m-building-farmers-shares-add|building_farmers_shares_add]] = `94`
    - [[vanilla/движок/Модификаторы B#^m-building-clerks-shares-add|building_clerks_shares_add]] = `9`

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Собственность|Собственность]]
- **Методы производства** (replacement_if_valid): [[grey_usu/Методы производства/Производственный кооператив (pm_company_headquarter_worker_cooperative)|Производственный кооператив (pm_company_headquarter_worker_cooperative)]]

---
type: concept
description: "Метод производства «pm_gate_basic_mage_tower» — grey USU 1.13, `pm_gate_basic_mage_tower`"
project: vic3
source: grey_usu
aliases: ["pm_gate_basic_mage_tower"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gate_basic_mage_tower
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/zzMoG_USU_manaflow_compat_pms.txt]
---
# pm_gate_basic_mage_tower

Метод производства · `pm_gate_basic_mage_tower` · `common/production_methods/zzMoG_USU_manaflow_compat_pms.txt:115`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gate_private_mages.dds`
- **disallowing_laws**: [[vanilla/Законы/Кооперативное владение|Кооперативное владение]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_gate_magical_innovation_add` = `0.5`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_gate_mages_add` = `30`
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `20` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_gate_mages_shares_add` = `94`
    - [[vanilla/движок/Модификаторы B#^m-building-clerks-shares-add|building_clerks_shares_add]] = `9`

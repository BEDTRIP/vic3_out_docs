---
type: concept
description: "Метод производства «pm_gate_cooperative_mage_tower» — grey USU 1.13, `pm_gate_cooperative_mage_tower`"
project: vic3
source: grey_usu
aliases: ["pm_gate_cooperative_mage_tower"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gate_cooperative_mage_tower
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/zzMoG_USU_manaflow_compat_pms.txt]
---
# pm_gate_cooperative_mage_tower

Метод производства · `pm_gate_cooperative_mage_tower` · `common/production_methods/zzMoG_USU_manaflow_compat_pms.txt:140`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/worker_cooperative.dds`
- **unlocking_laws**: [[vanilla/Законы/Кооперативное владение|Кооперативное владение]]
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_gate_magical_innovation_add` = `0.5`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_gate_mages_add` = `20`
    - `building_employment_clerks_add` = `30` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_gate_mages_shares_add` = `91`
    - `building_clerks_shares_add` = `6`

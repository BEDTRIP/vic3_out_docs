---
type: concept
description: "Метод производства «Imperial Administrative Center (pm_gbbf_dolmabahce_palace_active)» — Gates of Bosphorus 1.13, `pm_gbbf_dolmabahce_palace_active`"
project: vic3
source: gates_of_bosphorus
aliases: ["Imperial Administrative Center (pm_gbbf_dolmabahce_palace_active)", "Imperial Administrative Center", "pm_gbbf_dolmabahce_palace_active"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_dolmabahce_palace_active
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Imperial Administrative Center (pm_gbbf_dolmabahce_palace_active)

Метод производства · `pm_gbbf_dolmabahce_palace_active` · `common/production_methods/gbbf_08_monuments_methods.txt:84`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_administrative_building.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_prestige_add` = `15`
    - `country_authority_mult` = `0.05`
    - `country_bureaucracy_add` = `80`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_tax_capacity_add` = `15`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_paper_add` = `25` → [[vanilla/Товары/Бумага|Бумага]]
  - **level_scaled**:
    - `building_employment_bureaucrats_add` = `1000` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - `building_employment_clerks_add` = `4000` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **unlocking_production_methods**: `pm_gbbf_dolmabahce_palace_active`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Dolmabahçe Palace|Dolmabahçe Palace]]

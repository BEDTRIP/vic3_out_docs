---
type: concept
description: "Метод производства «Sovereign Wealth Fund» — PBE 1.13, `pm_company_headquarter_swg_3`"
project: vic3
source: pbe
aliases: ["Sovereign Wealth Fund", "pm_company_headquarter_swg_3"]
tags: [PBE, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_company_headquarter_swg_3
paths: [PowerBlocksExpanded/common/production_methods/vokaes_power_bloc_production_methods.txt]
---
# Sovereign Wealth Fund

Метод производства · `pm_company_headquarter_swg_3` · `common/production_methods/vokaes_power_bloc_production_methods.txt:21`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/privately_owned.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_principles**: `principle_sovereign_wealth_fund_3`
- **building_modifiers**:
  - **level_scaled**:
    - `building_employment_bureaucrats_add` = `5` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - `building_employment_clerks_add` = `-15` → [[vanilla/Население/Типы/Служащие|Служащие]]
  - **unscaled**:
    - `building_bureaucrats_shares_add` = `1`

## Ссылаются

- **Группы методов** (методы группы): [[pbe/Группы методов/Sovereign Wealth Fund|Sovereign Wealth Fund]]
- **Методы производства** (replacement_if_valid): [[pbe/Методы производства/No Effect (pm_company_headquarter_swg_no_effect)|No Effect (pm_company_headquarter_swg_no_effect)]]

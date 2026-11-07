---
type: concept
description: "Метод производства «Eerie Canal» — Hail Columbia 1.13, `pm_usfp_eerie_canal`"
project: vic3
source: hail_columbia
aliases: ["Eerie Canal", "pm_usfp_eerie_canal"]
tags: [hail_columbia, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_usfp_eerie_canal
paths: [for addon/Hail Columbia/common/production_methods/usfp_production_methods.txt]
---
# Eerie Canal

Метод производства · `pm_usfp_eerie_canal` · `common/production_methods/usfp_production_methods.txt:245`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/canals.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - `country_prestige_add` = `100`
- **state_modifiers**:
  - **unscaled**:
    - `state_migration_pull_mult` = `0.10`
    - `state_trade_advantage_mult` = `0.15`
    - `building_port_throughput_add` = `0.10` → [[vanilla/Здания/Порты|Порты]]
    - `state_market_access_price_impact` = `0.05`

## Ссылаются

- **Группы методов** (методы группы): [[hail_columbia/Группы методов/Eerie Canal|Eerie Canal]]

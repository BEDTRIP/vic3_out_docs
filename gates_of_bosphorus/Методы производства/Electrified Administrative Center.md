---
type: concept
description: "Метод производства «Electrified Administrative Center» — Gates of Bosphorus 1.13, `pm_gbbf_dolmabahce_palace_upgraded`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["Electrified Administrative Center", "pm_gbbf_dolmabahce_palace_upgraded"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_dolmabahce_palace_upgraded
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Electrified Administrative Center

Метод производства · `pm_gbbf_dolmabahce_palace_upgraded` · `common/production_methods/gbbf_08_monuments_methods.txt:112`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/gbbf_administrative_building.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `15`
    - [[vanilla/движок/Модификаторы C#^m-country-authority-mult|country_authority_mult]] = `0.05`
    - [[vanilla/движок/Модификаторы C#^m-country-bureaucracy-add|country_bureaucracy_add]] = `100`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-tax-capacity-add|state_tax_capacity_add]] = `30`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-paper-add|goods_input_paper_add]] = `20` → [[vanilla/Товары/Бумага|Бумага]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-telephones-add|goods_input_telephones_add]] = `5` → [[vanilla/Товары/Телефоны|Телефоны]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `2500` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `2500` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
- **unlocking_production_methods**: `pm_gbbf_dolmabahce_palace_upgraded`

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Dolmabahçe Palace|Dolmabahçe Palace]]

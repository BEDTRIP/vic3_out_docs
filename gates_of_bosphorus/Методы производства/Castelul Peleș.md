---
type: concept
description: "Метод производства «Castelul Peleș» — Gates of Bosphorus 1.13, `pm_gbbf_castelul_peles`"
project: vic3
source: gates_of_bosphorus
aliases: ["Castelul Peleș", "pm_gbbf_castelul_peles"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_castelul_peles
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# Castelul Peleș

Метод производства · `pm_gbbf_castelul_peles` · `common/production_methods/gbbf_08_monuments_methods.txt:20`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-loyalists-from-legitimacy-mult|country_loyalists_from_legitimacy_mult]] = `0.1`
    - [[vanilla/движок/Модификаторы C#^m-country-authority-add|country_authority_add]] = `50`
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Castelul Peleș|Castelul Peleș]]

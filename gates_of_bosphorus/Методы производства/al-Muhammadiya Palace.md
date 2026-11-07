---
type: concept
description: "Метод производства «al-Muhammadiya Palace» — Gates of Bosphorus 1.13, `pm_gbbf_mohamedia_palace`"
project: vic3
audience: agent
source: gates_of_bosphorus
aliases: ["al-Muhammadiya Palace", "pm_gbbf_mohamedia_palace"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_mohamedia_palace
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_08_monuments_methods.txt]
---
# al-Muhammadiya Palace

Метод производства · `pm_gbbf_mohamedia_palace` · `common/production_methods/gbbf_08_monuments_methods.txt:352`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/wonders.dds`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-authority-mult|country_authority_mult]] = `0.10`
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`
- **building_modifiers**:
  - **workforce_scaled**: пусто
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `100` → [[vanilla/Население/Типы/Чиновники|Чиновники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `400` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/al-Muhammadiya Palace|al-Muhammadiya Palace]]

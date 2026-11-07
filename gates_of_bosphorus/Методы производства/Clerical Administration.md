---
type: concept
description: "Метод производства «Clerical Administration» — Gates of Bosphorus 1.13, `pm_gbbf_clerical_administration`"
project: vic3
source: gates_of_bosphorus
aliases: ["Clerical Administration", "pm_gbbf_clerical_administration"]
tags: [gates_of_bosphorus, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gbbf_clerical_administration
paths: [for addon/gatesofbosphorus/common/production_methods/gbbf_07_government_methods.txt]
---
# Clerical Administration

Метод производства · `pm_gbbf_clerical_administration` · `common/production_methods/gbbf_07_government_methods.txt:216`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/ownership_clergy.dds`
- **disallowing_laws**: [[vanilla/Законы/Полное разделение|Полное разделение]], [[vanilla/Законы/Государственный атеизм|Государственный атеизм]]
- **building_modifiers**:
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clergymen-add|building_employment_clergymen_add]] = `50` → [[vanilla/Население/Типы/Священнослужители|Священнослужители]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-bureaucrats-add|building_employment_bureaucrats_add]] = `50` → [[vanilla/Население/Типы/Чиновники|Чиновники]]

## Ссылаются

- **Группы методов** (методы группы): [[gates_of_bosphorus/Группы методов/Administrative System|Administrative System]]

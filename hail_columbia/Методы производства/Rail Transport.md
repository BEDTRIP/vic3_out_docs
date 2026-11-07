---
type: concept
description: "Метод производства «Rail Transport» — Hail Columbia 1.13, `usfp_pm_fur_rail_hunting`"
project: vic3
source: hail_columbia
aliases: ["Rail Transport", "usfp_pm_fur_rail_hunting"]
tags: [hail_columbia, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: usfp_pm_fur_rail_hunting
paths: [for addon/Hail Columbia/common/production_methods/usfp_production_methods.txt]
---
# Rail Transport

Метод производства · `usfp_pm_fur_rail_hunting` · `common/production_methods/usfp_production_methods.txt:106`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_transport.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `2`
- **unlocking_technologies**: [[vanilla/Технологии/Стальные вагоны|Стальные вагоны]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_transportation_add` = `2` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-200` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
  - **unscaled**:
    - `building_laborers_mortality_mult` = `0.1`
    - `building_soldiers_mortality_mult` = `0.1`

## Ссылаются

- **Группы методов** (методы группы): [[hail_columbia/Группы методов/Transportation|Transportation]]

---
type: concept
description: "Метод производства «Solar Panels» — T&R 1.13, `pm_solar_panels`"
project: vic3
source: tr
aliases: ["Solar Panels", "pm_solar_panels"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_solar_panels
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Solar Panels

Метод производства · `pm_solar_panels` · `common/production_methods/ztr_energy_production_methods.txt:1319`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_solar_panels.dds`
- **unlocking_technologies**: [[tr/Технологии/Advanced Solar Panels|Advanced Solar Panels]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_rare_earths_add` = `2` → [[tr/Товары/Rare Earths|Rare Earths]]
    - `goods_input_advancedores_add` = `5` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_input_batteries_add` = `15` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_output_global_electricity_add` = `100` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `700` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Renewable Energy Plant|Renewable Energy Plant]]

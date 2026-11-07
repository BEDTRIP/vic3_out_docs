---
type: concept
description: "Метод производства «Rudimental Photovoltaic Cells» — T&R 1.13, `pm_rudimental_photovoltaic_cells`"
project: vic3
audience: agent
source: tr
aliases: ["Rudimental Photovoltaic Cells", "pm_rudimental_photovoltaic_cells"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rudimental_photovoltaic_cells
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_energy_production_methods.txt]
---
# Rudimental Photovoltaic Cells

Метод производства · `pm_rudimental_photovoltaic_cells` · `common/production_methods/ztr_energy_production_methods.txt:1272`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_rudimental_photovoltaic_cells.dds`
- **unlocking_technologies**: [[tr/Технологии/Photoelectric Effect|Photoelectric Effect]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_plastics_add` = `10` → [[tr/Товары/Пластмассы|Пластмассы]]
    - `goods_input_batteries_add` = `6` → [[tr/Товары/Batteries|Batteries]]
    - `goods_input_advancedores_add` = `4` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - `goods_output_global_electricity_add` = `50` → [[tr/Товары/National Electricity|National Electricity]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `900` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Renewable Energy Plant|Renewable Energy Plant]]

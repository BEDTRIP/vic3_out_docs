---
type: concept
description: "Метод производства «Quartz Glass» — T&R 1.13, `pm_quartz_glass`"
project: vic3
audience: agent
source: tr
aliases: ["Quartz Glass", "pm_quartz_glass"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_quartz_glass
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Quartz Glass

Метод производства · `pm_quartz_glass` · `common/production_methods/ztr_new_production_methods.txt:6077`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_quartz_glass.dds`
- **unlocking_technologies**: [[tr/Технологии/Quartz Glass|Quartz Glass]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_advancedores_add` = `15` → [[tr/Товары/Advanced Ores|Advanced Ores]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-lead-add|goods_input_lead_add]] = `-5` → [[vanilla/Товары/Свинец|Свинец]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-glass-add|goods_output_glass_add]] = `-30` → [[vanilla/Товары/Стекло|Стекло]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-porcelain-add|goods_output_porcelain_add]] = `35` → [[vanilla/Товары/Фарфор|Фарфор]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-glassworks-throughput-add|building_glassworks_throughput_add]] = `0.1` → [[tr/Здания/Стеклозаводы|Стеклозаводы]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Производство предметов роскоши (pmg_luxury_building_glassworks)|Производство предметов роскоши (pmg_luxury_building_glassworks)]]

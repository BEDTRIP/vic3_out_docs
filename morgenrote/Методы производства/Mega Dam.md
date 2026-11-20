---
type: explanation
description: "Метод производства «Mega Dam» — Morgenröte 1.15.2, `pm_tesla_mega_dam`"
project: vic3
audience: agent
source: morgenrote
aliases: ["Mega Dam", "pm_tesla_mega_dam"]
tags: [Morgenröte, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_tesla_mega_dam
paths: [Morgenrote/common/production_methods/mr_science_tesla_production_methods.txt]
---
# Mega Dam

Метод производства · `pm_tesla_mega_dam` · `common/production_methods/mr_science_tesla_production_methods.txt:144`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/tesla_mega_dam_pm.dds`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `200` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `300` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-copper-add|goods_input_copper_add]] = `5` → [[vanilla/Товары/Медь|Медь]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `5` → [[vanilla/Товары/Двигатели|Двигатели]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `10` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `1000` → [[vanilla/Товары/Электричество|Электричество]]
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `25`
- **country_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы C#^m-country-prestige-add|country_prestige_add]] = `25`

## Ссылаются

- **Группы методов** (методы группы): [[morgenrote/Группы методов/Mega Dam|Mega Dam]]

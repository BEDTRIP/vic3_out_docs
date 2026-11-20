---
type: explanation
description: "Метод производства «Production» — Morgenröte 1.15.2, `pm_mendelejew_helium_production`"
project: vic3
audience: agent
source: morgenrote
aliases: ["Production", "pm_mendelejew_helium_production"]
tags: [Morgenröte, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_mendelejew_helium_production
paths: [Morgenrote/common/production_methods/mr_science_mendelejew_production_methods.txt]
---
# Production

Метод производства · `pm_mendelejew_helium_production` · `common/production_methods/mr_science_mendelejew_production_methods.txt:188`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_mendelejew_helium_production_pm.dds`
- **unlocking_technologies**: пусто
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-oil-add|goods_output_oil_add]] = `50` → [[vanilla/Товары/ГСМ|ГСМ]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `300` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `200` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
- **country_modifiers**:
  - **unscaled**:
    - `country_curtiss_decorative_helium_reserve_boolean` = `yes`
- **ai_value**: `3000`

## Ссылаются

- **Группы методов** (методы группы): [[morgenrote/Группы методов/Production|Production]]

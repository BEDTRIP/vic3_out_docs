---
type: concept
description: "Метод производства «Condensing Engine Pump (pm_curie_condensing_engine_pump_building_uranium_mine)» — T&R 1.13, `pm_curie_condensing_engine_pump_building_uranium_mine`"
project: vic3
source: tr
aliases: ["Condensing Engine Pump (pm_curie_condensing_engine_pump_building_uranium_mine)", "Condensing Engine Pump", "pm_curie_condensing_engine_pump_building_uranium_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_curie_condensing_engine_pump_building_uranium_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_modified_mr_production_methods.txt]
---
# Condensing Engine Pump (pm_curie_condensing_engine_pump_building_uranium_mine)

Метод производства · `pm_curie_condensing_engine_pump_building_uranium_mine` · `common/production_methods/ztr_modified_mr_production_methods.txt:956`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/condensing_engine_pump.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Водотрубный котёл|Водотрубный котёл]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-tools-add|goods_input_tools_add]] = `15` → [[vanilla/Товары/Инструменты|Инструменты]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-coal-add|goods_input_coal_add]] = `15` → [[vanilla/Товары/Уголь|Уголь]]
    - `goods_output_good_uranium_add` = `60` → [[tr/Товары/Uranium|Uranium]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `3000` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1000` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `500` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
  - **unscaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-laborers-mortality-mult|building_laborers_mortality_mult]] = `0.2`

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Mining equipment (pmg_curie_mining_equipment_building_uranium_mine)|Mining equipment (pmg_curie_mining_equipment_building_uranium_mine)]]

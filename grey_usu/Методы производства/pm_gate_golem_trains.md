---
type: concept
description: "Метод производства «pm_gate_golem_trains» — grey USU 1.13, `pm_gate_golem_trains`"
project: vic3
audience: agent
source: grey_usu
aliases: ["pm_gate_golem_trains"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_gate_golem_trains
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/zzMoG_USU_manaflow_compat_pms.txt]
---
# pm_gate_golem_trains

Метод производства · `pm_gate_golem_trains` · `common/production_methods/zzMoG_USU_manaflow_compat_pms.txt:72`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/trains_electric.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_technologies**: `gate_magic_golems`
- **unlocking_production_methods**: [[grey_usu/Методы производства/Пассажирские вагоны с электроприводом|Пассажирские вагоны с электроприводом]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-engines-add|goods_input_engines_add]] = `2` → [[vanilla/Товары/Двигатели|Двигатели]]
    - `goods_input_gate_mana_core_add` = `3`
    - `goods_input_gate_mana_add` = `8`
    - `goods_input_gate_golem_add` = `2`
    - [[vanilla/движок/Модификаторы G#^m-goods-output-transportation-add|goods_output_transportation_add]] = `70` → [[grey_usu/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `800` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `100` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `50` → [[vanilla/Население/Типы/Инженеры|Инженеры]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-clerks-add|building_employment_clerks_add]] = `200` → [[vanilla/Население/Типы/Служащие|Служащие]]
    - `building_employment_gate_mages_add` = `450`
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-market-access-price-impact|state_market_access_price_impact]] = `0.04`
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `10`
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-infrastructure-add|state_infrastructure_add]] = `20`

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Основа (pmg_base_building_railway)|Основа (pmg_base_building_railway)]]

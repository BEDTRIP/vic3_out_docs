---
type: concept
description: "Метод производства «Перевозка по рельсам (pm_rail_transport_mine)» — TGR 1.15, `pm_rail_transport_mine`"
project: vic3
audience: agent
source: tgr
aliases: ["Перевозка по рельсам (pm_rail_transport_mine)", "Перевозка по рельсам", "pm_rail_transport_mine"]
tags: [TGR, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rail_transport_mine
paths: [TheGreatRevision/common/production_methods/TGR_TRADE_automation.txt]
replaces: "[[vanilla/Методы производства/Перевозка по рельсам (pm_rail_transport_mine)]]"
---
# Перевозка по рельсам (pm_rail_transport_mine)

Метод производства · `pm_rail_transport_mine` · `common/production_methods/TGR_TRADE_automation.txt:61`

## Отличия от ваниль

- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_transport.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `10`
- **unlocking_technologies**: [[vanilla/Технологии/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `2` → [[tgr/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-1500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

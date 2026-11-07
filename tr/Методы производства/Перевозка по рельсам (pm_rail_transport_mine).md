---
type: concept
description: "Метод производства «Перевозка по рельсам (pm_rail_transport_mine)» — T&R 1.13, `pm_rail_transport_mine`"
project: vic3
audience: agent
source: tr
aliases: ["Перевозка по рельсам (pm_rail_transport_mine)", "Перевозка по рельсам", "pm_rail_transport_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_rail_transport_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
replaces: "[[vanilla/Методы производства/Перевозка по рельсам (pm_rail_transport_mine)]]"
---
# Перевозка по рельсам (pm_rail_transport_mine)

Метод производства · `pm_rail_transport_mine` · `common/production_methods/ztr_new_production_methods.txt:369`

## Отличия от ваниль

- **state_modifiers**: изменено
- **building_modifiers**: изменено

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/rail_transport.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-generation-add|state_pollution_generation_add]] = `5`
- **unlocking_technologies**: [[vanilla/Технологии/Железные дороги|Железные дороги]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-transportation-add|goods_input_transportation_add]] = `4` → [[vanilla/Товары/Перевозка|Перевозка]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `-800` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Train Automation (pmg_curie_train_automation_building_uranium_mine)|Train Automation (pmg_curie_train_automation_building_uranium_mine)]], [[tr/Группы методов/Train Automation (pmg_train_automation_building_advancedores_mine)|Train Automation (pmg_train_automation_building_advancedores_mine)]], [[tr/Группы методов/Train Automation (pmg_train_automation_building_bauxite_mine)|Train Automation (pmg_train_automation_building_bauxite_mine)]], [[tr/Группы методов/Train Automation (pmg_train_automation_building_commonores_mine)|Train Automation (pmg_train_automation_building_commonores_mine)]], [[tr/Группы методов/Train Automation (pmg_train_automation_building_copper_mine)|Train Automation (pmg_train_automation_building_copper_mine)]], [[tr/Группы методов/Train Automation (pmg_train_automation_building_rare_earths_mine)|Train Automation (pmg_train_automation_building_rare_earths_mine)]], [[tr/Группы методов/Transport (pmg_transport_automation_building_general)|Transport (pmg_transport_automation_building_general)]]

---
type: concept
description: "Метод производства «Versatile Transportation (pm_multiway_transport_mine)» — T&R 1.13, `pm_multiway_transport_mine`"
project: vic3
source: tr
aliases: ["Versatile Transportation (pm_multiway_transport_mine)", "Versatile Transportation", "pm_multiway_transport_mine"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_multiway_transport_mine
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Versatile Transportation (pm_multiway_transport_mine)

Метод производства · `pm_multiway_transport_mine` · `common/production_methods/ztr_new_production_methods.txt:393`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_multiway_transport_building.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `5`
- **unlocking_technologies**: [[tr/Технологии/Modern Vehicles|Modern Vehicles]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_transportation_add` = `2` → [[vanilla/Товары/Перевозка|Перевозка]]
    - `goods_input_automobiles_add` = `2` → [[tr/Товары/Автомобили|Автомобили]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `-1250` → [[vanilla/Население/Типы/Рабочие|Рабочие]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Train Automation (pmg_curie_train_automation_building_uranium_mine)|Train Automation (pmg_curie_train_automation_building_uranium_mine)]], [[tr/Группы методов/Train Automation (pmg_train_automation_building_advancedores_mine)|Train Automation (pmg_train_automation_building_advancedores_mine)]], [[tr/Группы методов/Train Automation (pmg_train_automation_building_bauxite_mine)|Train Automation (pmg_train_automation_building_bauxite_mine)]], [[tr/Группы методов/Train Automation (pmg_train_automation_building_commonores_mine)|Train Automation (pmg_train_automation_building_commonores_mine)]], [[tr/Группы методов/Train Automation (pmg_train_automation_building_copper_mine)|Train Automation (pmg_train_automation_building_copper_mine)]], [[tr/Группы методов/Train Automation (pmg_train_automation_building_rare_earths_mine)|Train Automation (pmg_train_automation_building_rare_earths_mine)]], [[tr/Группы методов/Transport (pmg_transport_automation_building_general)|Transport (pmg_transport_automation_building_general)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_coal_mine)|Использование поездов (pmg_train_automation_building_coal_mine)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_gold_mine)|Использование поездов (pmg_train_automation_building_gold_mine)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_iron_mine)|Использование поездов (pmg_train_automation_building_iron_mine)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_lead_mine)|Использование поездов (pmg_train_automation_building_lead_mine)]], [[tr/Группы методов/Использование поездов (pmg_train_automation_building_sulfur_mine)|Использование поездов (pmg_train_automation_building_sulfur_mine)]]

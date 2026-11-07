---
type: concept
description: "Метод производства «Waste Incinerator» — T&R 1.13, `pm_waste_incinerator`"
project: vic3
source: tr
aliases: ["Waste Incinerator", "pm_waste_incinerator"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_waste_incinerator
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Waste Incinerator

Метод производства · `pm_waste_incinerator` · `common/production_methods/ztr_new_production_methods.txt:9188`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/waste_incinerator.dds`
- **state_modifiers**:
  - **workforce_scaled**:
    - `state_pollution_generation_add` = `3`
- **unlocking_production_methods**: [[tr/Методы производства/Электрическое освещение улиц|Электрическое освещение улиц]], [[tr/Методы производства/Modern Urban Utilities|Modern Urban Utilities]], [[tr/Методы производства/Smart City Services|Smart City Services]]
- **unlocking_technologies**: [[vanilla/Технологии/ГСМ-турбина|ГСМ-турбина]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electricity_add` = `-2` → [[vanilla/Товары/Электричество|Электричество]]
- **disallowing_laws**: [[tr/Законы/Active Restoration|Active Restoration]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Recycling Center|Recycling Center]]

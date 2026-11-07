---
type: concept
description: "Метод производства «Smart City Services» — T&R 1.13, `pm_smart_city_infrastructure`"
project: vic3
source: tr
aliases: ["Smart City Services", "pm_smart_city_infrastructure"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_smart_city_infrastructure
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Smart City Services

Метод производства · `pm_smart_city_infrastructure` · `common/production_methods/ztr_new_production_methods.txt:6910`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_enviromental_services.dds`
- **city_lights_color_index**: `2`
- **state_modifiers**:
  - **unscaled**:
    - `state_mortality_mult` = `-0.02`
    - `state_pollution_reduction_health_mult` = `-0.05`
  - **workforce_scaled**:
    - `state_infrastructure_add` = `3`
- **unlocking_technologies**: [[tr/Технологии/Urban Sustainability|Urban Sustainability]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_alloys_add` = `0.5` → [[tr/Товары/Alloys|Alloys]]
    - `goods_input_electricity_add` = `8` → [[vanilla/Товары/Электричество|Электричество]]
    - `goods_input_copperwires_add` = `4` → [[tr/Товары/Wires|Wires]]
    - `goods_input_telecommunications_add` = `10` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_output_services_add` = `35` → [[vanilla/Товары/Услуги|Услуги]]
  - **level_scaled**:
    - `building_employment_laborers_add` = `50` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - `building_employment_engineers_add` = `100` → [[tr/Население/Типы/Инженеры|Инженеры]]
    - `building_employment_clerks_add` = `50` → [[vanilla/Население/Типы/Служащие|Служащие]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Уличное освещение|Уличное освещение]]
- **Методы производства** (unlocking_production_methods): [[tr/Методы производства/Waste Incinerator|Waste Incinerator]]

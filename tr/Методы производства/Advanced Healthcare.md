---
type: concept
description: "Метод производства «Advanced Healthcare» — T&R 1.13, `pm_advanced_healtcare`"
project: vic3
audience: agent
source: tr
aliases: ["Advanced Healthcare", "pm_advanced_healtcare"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_advanced_healtcare
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Advanced Healthcare

Метод производства · `pm_advanced_healtcare` · `common/production_methods/ztr_new_production_methods.txt:7060`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/panum_hospital_pm.dds`
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.2`
    - [[vanilla/движок/Модификаторы S#^m-state-mortality-turmoil-mult|state_mortality_turmoil_mult]] = `-0.2`
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.2`
- **unlocking_technologies**: [[tr/Технологии/MRI Development|MRI Development]]
- **disallowing_laws**: [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]], [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_processors_add` = `1` → [[tr/Товары/Processors|Processors]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `3` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_input_pharmaceuticals_add` = `10` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `35` → [[vanilla/Товары/Услуги|Услуги]]
- **required_input_goods**: [[vanilla/Товары/Электричество|Электричество]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Healthcare|Healthcare]]

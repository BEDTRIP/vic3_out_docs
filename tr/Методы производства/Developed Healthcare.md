---
type: concept
description: "Метод производства «Developed Healthcare» — T&R 1.13, `pm_developed_healtcare`"
project: vic3
audience: agent
source: tr
aliases: ["Developed Healthcare", "pm_developed_healtcare"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_developed_healtcare
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Developed Healthcare

Метод производства · `pm_developed_healtcare` · `common/production_methods/ztr_new_production_methods.txt:7031`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_developed_healtcare.dds`
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.15`
    - [[vanilla/движок/Модификаторы S#^m-state-mortality-turmoil-mult|state_mortality_turmoil_mult]] = `-0.15`
    - [[vanilla/движок/Модификаторы S#^m-state-pollution-reduction-health-mult|state_pollution_reduction_health_mult]] = `-0.1`
- **unlocking_technologies**: [[tr/Технологии/Vaccination Campaigns|Vaccination Campaigns]]
- **disallowing_laws**: [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]], [[vanilla/Законы/Благотворительные лечебницы|Благотворительные лечебницы]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_electroniccomponents_add` = `1` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `3` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_input_pharmaceuticals_add` = `5` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `20` → [[vanilla/Товары/Услуги|Услуги]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Healthcare|Healthcare]]

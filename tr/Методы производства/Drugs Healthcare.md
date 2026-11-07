---
type: concept
description: "Метод производства «Drugs Healthcare» — T&R 1.13, `pm_drugs_healtcare`"
project: vic3
audience: agent
source: tr
aliases: ["Drugs Healthcare", "pm_drugs_healtcare"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_drugs_healtcare
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Drugs Healthcare

Метод производства · `pm_drugs_healtcare` · `common/production_methods/ztr_new_production_methods.txt:6980`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/panum_clinic_pm_drugs.dds`
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.1`
    - [[vanilla/движок/Модификаторы S#^m-state-mortality-turmoil-mult|state_mortality_turmoil_mult]] = `-0.1`
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `2` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-opium-add|goods_input_opium_add]] = `2` → [[vanilla/Товары/Опиум|Опиум]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-liquor-add|goods_input_liquor_add]] = `2` → [[vanilla/Товары/Спирт|Спирт]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `10` → [[vanilla/Товары/Услуги|Услуги]]
- **disallowing_laws**: [[vanilla/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]], [[vanilla/Законы/Государственное медицинское страхование|Государственное медицинское страхование]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Healthcare|Healthcare]]

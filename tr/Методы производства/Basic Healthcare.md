---
type: concept
description: "Метод производства «Basic Healthcare» — T&R 1.13, `pm_basic_healtcare`"
project: vic3
source: tr
aliases: ["Basic Healthcare", "pm_basic_healtcare"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_basic_healtcare
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Basic Healthcare

Метод производства · `pm_basic_healtcare` · `common/production_methods/ztr_new_production_methods.txt:6958`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/panum_clinic_pm.dds`
- **state_modifiers**:
  - **unscaled**:
    - `state_mortality_turmoil_mult` = `-0.1`
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_fabric_add` = `2` → [[vanilla/Товары/Ткань|Ткань]]
    - `goods_input_liquor_add` = `2` → [[vanilla/Товары/Спирт|Спирт]]
    - `goods_output_services_add` = `5` → [[vanilla/Товары/Услуги|Услуги]]
- **disallowing_laws**: [[vanilla/Законы/Индивидуальное медицинское страхование|Индивидуальное медицинское страхование]], [[vanilla/Законы/Государственное медицинское страхование|Государственное медицинское страхование]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Healthcare|Healthcare]]

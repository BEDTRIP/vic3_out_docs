---
type: concept
description: "Метод производства «Modern Healthcare» — T&R 1.13, `pm_modern_healtcare`"
project: vic3
source: tr
aliases: ["Modern Healthcare", "pm_modern_healtcare"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_modern_healtcare
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Modern Healthcare

Метод производства · `pm_modern_healtcare` · `common/production_methods/ztr_new_production_methods.txt:7004`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_modern_healtcare.dds`
- **state_modifiers**:
  - **unscaled**:
    - [[vanilla/движок/Модификаторы S#^m-state-turmoil-effects-mult|state_turmoil_effects_mult]] = `-0.15`
    - [[vanilla/движок/Модификаторы S#^m-state-mortality-turmoil-mult|state_mortality_turmoil_mult]] = `-0.15`
- **unlocking_technologies**: [[tr/Технологии/Фармацевтика|Фармацевтика]]
- **disallowing_laws**: [[vanilla/Законы/Нет системы здравоохранения|Нет системы здравоохранения]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-fabric-add|goods_input_fabric_add]] = `3` → [[vanilla/Товары/Ткань|Ткань]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-liquor-add|goods_input_liquor_add]] = `1` → [[vanilla/Товары/Спирт|Спирт]]
    - `goods_input_pharmaceuticals_add` = `2` → [[tr/Товары/Фармацевтика|Фармацевтика]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-services-add|goods_output_services_add]] = `10` → [[vanilla/Товары/Услуги|Услуги]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Healthcare|Healthcare]]

---
type: concept
description: "Метод производства «Смешанное электроснабжение (PPP_pm_t1_hybrid_power)» — grey USU 1.13, `PPP_pm_t1_hybrid_power`"
project: vic3
source: grey_usu
aliases: ["Смешанное электроснабжение (PPP_pm_t1_hybrid_power)", "Mixed Grid Supply", "PPP_pm_t1_hybrid_power"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: PPP_pm_t1_hybrid_power
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_PPhy_new_prod_methods.txt]
---
# Смешанное электроснабжение (PPP_pm_t1_hybrid_power)

Метод производства · `PPP_pm_t1_hybrid_power` · `common/production_methods/yMoG_USU_PPhy_new_prod_methods.txt:190`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/PPP_hybrid_power.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_production_methods**: [[grey_usu/Методы производства/Ранние турбины|Ранние турбины]]
- **unlocking_technologies**: [[grey_usu/Технологии/Передача мощности|Передача мощности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `-24` → [[grey_usu/Товары/Электричество|Электричество]]
    - `goods_output_ppp_hv_power_add` = `10` → [[grey_usu/Товары/Высоковольтная мощность|Высоковольтная мощность]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Распределение электроэнергии|Распределение электроэнергии]]
- **Методы производства** (replacement_if_valid): [[grey_usu/Методы производства/Местная электроэнергия (PPP_pm_t1_local_power)|Местная электроэнергия (PPP_pm_t1_local_power)]]

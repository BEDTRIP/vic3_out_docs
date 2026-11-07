---
type: concept
description: "Метод производства «Смешанная сетевая поставка (PPP_pm_gt_hybrid_power)» — grey USU 1.13, `PPP_pm_gt_hybrid_power`"
project: vic3
audience: agent
source: grey_usu
aliases: ["Смешанная сетевая поставка (PPP_pm_gt_hybrid_power)", "Mixed Grid Supply", "PPP_pm_gt_hybrid_power"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: PPP_pm_gt_hybrid_power
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_PPP_new_prod_methods.txt]
---
# Смешанная сетевая поставка (PPP_pm_gt_hybrid_power)

Метод производства · `PPP_pm_gt_hybrid_power` · `common/production_methods/yMoG_USU_PPP_new_prod_methods.txt:265`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/PPP_hybrid_power.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_production_methods**: [[grey_usu/Методы производства/Газовые турбины|Газовые турбины]]
- **unlocking_technologies**: [[grey_usu/Технологии/Передача мощности|Передача мощности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-output-electricity-add|goods_output_electricity_add]] = `-70` → [[grey_usu/Товары/Электричество|Электричество]]
    - `goods_output_ppp_hv_power_add` = `20` → [[grey_usu/Товары/Высоковольтная мощность|Высоковольтная мощность]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Распределение мощности|Распределение мощности]]
- **Методы производства** (replacement_if_valid): [[grey_usu/Методы производства/Местное электричество (PPP_pm_gt_local_power)|Местное электричество (PPP_pm_gt_local_power)]]

---
type: concept
description: "Метод производства «Смешанная сетевая поставка (PPP_pm_se_hybrid_power)» — grey USU 1.13, `PPP_pm_se_hybrid_power`"
project: vic3
source: grey_usu
aliases: ["Смешанная сетевая поставка (PPP_pm_se_hybrid_power)", "Mixed Grid Supply", "PPP_pm_se_hybrid_power"]
tags: [grey_usu, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: PPP_pm_se_hybrid_power
paths: [grey_add_alot_of_things/grey_usu/common/production_methods/yMoG_USU_PPP_new_prod_methods.txt]
---
# Смешанная сетевая поставка (PPP_pm_se_hybrid_power)

Метод производства · `PPP_pm_se_hybrid_power` · `common/production_methods/yMoG_USU_PPP_new_prod_methods.txt:161`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/PPP_hybrid_power.dds`
- **is_hidden_when_unavailable**: `yes`
- **unlocking_production_methods**: [[grey_usu/Методы производства/Паровые двигатели|Паровые двигатели]]
- **unlocking_technologies**: [[grey_usu/Технологии/Передача мощности|Передача мощности]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_output_electricity_add` = `-42` → [[grey_usu/Товары/Электричество|Электричество]]
    - `goods_output_ppp_hv_power_add` = `12` → [[grey_usu/Товары/Высоковольтная мощность|Высоковольтная мощность]]

## Ссылаются

- **Группы методов** (методы группы): [[grey_usu/Группы методов/Распределение мощности|Распределение мощности]]
- **Методы производства** (replacement_if_valid): [[grey_usu/Методы производства/Местное электричество (PPP_pm_se_local_power)|Местное электричество (PPP_pm_se_local_power)]]

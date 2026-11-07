---
type: concept
description: "Метод производства «Launched Guided Projectiles» — T&R 1.13, `pm_launched_guided_projectiles`"
project: vic3
audience: agent
source: tr
aliases: ["Launched Guided Projectiles", "pm_launched_guided_projectiles"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_launched_guided_projectiles
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Launched Guided Projectiles

Метод производства · `pm_launched_guided_projectiles` · `common/production_methods/ztr_new_production_methods.txt:9151`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_launched_guided_projectiles.dds`
- **unlocking_technologies**: [[tr/Технологии/Cannon-Launched Guided Projectiles|Cannon-Launched Guided Projectiles]]
- **building_modifiers**:
  - **workforce_scaled**:
    - [[vanilla/движок/Модификаторы G#^m-goods-input-explosives-add|goods_input_explosives_add]] = `45` → [[vanilla/Товары/Взрывчатка|Взрывчатка]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-lead-add|goods_input_lead_add]] = `20` → [[vanilla/Товары/Свинец|Свинец]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `30` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_electroniccomponents_add` = `5` → [[tr/Товары/Electronic Components|Electronic Components]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-ammunition-add|goods_output_ammunition_add]] = `130` → [[vanilla/Товары/Боеприпасы|Боеприпасы]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-shopkeepers-add|building_employment_shopkeepers_add]] = `500` → [[vanilla/Население/Типы/Лавочники|Лавочники]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-laborers-add|building_employment_laborers_add]] = `2500` → [[vanilla/Население/Типы/Рабочие|Рабочие]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-machinists-add|building_employment_machinists_add]] = `1250` → [[vanilla/Население/Типы/Механики|Механики]]
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `750` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Основа (pmg_base_building_munition_plant)|Основа (pmg_base_building_munition_plant)]]

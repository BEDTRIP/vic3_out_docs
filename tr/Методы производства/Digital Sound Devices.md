---
type: concept
description: "Метод производства «Digital Sound Devices» — T&R 1.13, `pm_digital_sound_devices`"
project: vic3
source: tr
aliases: ["Digital Sound Devices", "pm_digital_sound_devices"]
tags: [tr, метод-производства]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: pm_digital_sound_devices
paths: [TechRes+Kuromi/t&r/common/production_methods/ztr_new_production_methods.txt]
---
# Digital Sound Devices

Метод производства · `pm_digital_sound_devices` · `common/production_methods/ztr_new_production_methods.txt:3853`

## Поля

- **texture**: `gfx/interface/icons/production_method_icons/pm_digital_sound_devices.dds`
- **unlocking_technologies**: [[tr/Технологии/Mobile Phone|Mobile Phone]]
- **building_modifiers**:
  - **workforce_scaled**:
    - `goods_input_manzoni_prints_add` = `10` → [[tr/Товары/Media Content|Media Content]]
    - [[vanilla/движок/Модификаторы G#^m-goods-input-steel-add|goods_input_steel_add]] = `20` → [[vanilla/Товары/Сталь|Сталь]]
    - `goods_input_telecommunications_add` = `30` → [[tr/Товары/Telecommunications|Telecommunications]]
    - `goods_input_softwares_add` = `5` → [[tr/Товары/Software|Software]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-telephones-add|goods_output_telephones_add]] = `-45` → [[vanilla/Товары/Телефоны|Телефоны]]
    - [[vanilla/движок/Модификаторы G#^m-goods-output-radios-add|goods_output_radios_add]] = `95` → [[vanilla/Товары/Радио|Радио]]
  - **level_scaled**:
    - [[vanilla/движок/Модификаторы B#^m-building-employment-engineers-add|building_employment_engineers_add]] = `250` → [[tr/Население/Типы/Инженеры|Инженеры]]

## Ссылаются

- **Группы методов** (методы группы): [[tr/Группы методов/Радио|Радио]]

---
type: history
kind: research
description: "Сводка MMRPA: что мод меняет относительно ванили 1.13 — разбор по файлам до этапа ДОК; исходный материал для графа источника, ключи сверены 12.11 со снимком 1.15, смысл — нет"
project: vic3
audience: agent
source: mmrpa
tags: [источники, сводка]
date: 2026-01-17
---
> Сводка из `vic3_mods/сводки по модам/сводка_mmra.md` (последняя правка 2026-01-17), перенесена без правок текста; снимок мода — `vic3_mods_out/MMRPA/`.

> **Сверка 12.11 (снимок 1.15, этап ОБН, Д.ОБН.6) — по ключам, смысл не сверен.** Мод на снимке 1.13 — файлы мода с этапа ДОК не менялись. Из 26 имён в `…` нашлись в снимке мода или ваниль 10; устарело: все ключи методов железной дороги — в снимке MMRPA только картинки, ключи не проверить. Что мод меняет на текущем снимке — генерат «Что меняет в ванили» этой папки; он главнее сводки.

Сводка изменений:

- **Железные дороги: замена базовых ПМ поездов.** В `production_methods` все ПМ поездов определены через `REPLACE_OR_CREATE`, то есть переопределяют ваниль: `pm_early_trains`, `pm_steam_trains`, `pm_steam_trains_principle_transport_3`, `pm_electric_trains`, `pm_electric_trains_principle_transport_3`, `pm_diesel_trains`, `pm_diesel_trains_principle_transport_3`.
- **Баланс поездов:** снижены некоторые входы (особенно уголь/электричество), немного подправлен выпуск транспорта; для паровых/электрических/дизельных поездов добавлен `state_market_access_price_impact` (0.025–0.15). Например, `pm_steam_trains` уменьшает уголь до 3 (было 5) и даёт `+0.025` к влиянию на цену доступа к рынку.
- **Новые пассажирские вагоны (электрические):** добавлен `pm_electric_passenger_carriages` (сталь + электричество, больше транспорта, больше служащих/машинистов). Этот ПМ добавлен в группу пассажирских поездов.
- **Новые группы ПМ для железных дорог:**  
  - `pmg_gauges_building_railway` (колея): `pm_narrow_gauge_railway`, `pm_standard_gauge_railway`, `pm_broad_gauge_railway`, `pm_electrified_railway`. Влияют на транспорт, занятость и инфраструктуру (узкая — штрафы, широкая — бонусы, электрификация — требует электричества).  
  - `pmg_automation_building_railway` (автоматизация): `pm_auto_disabled_building_railway`, `pm_watertube_boiler_building_railway`, `pm_rotary_valve_engine_building_railway`, `pm_steam_donkey_building_railway`. Дают расход инструментов/угля/двигателей, снижают занятость рабочих и добавляют загрязнение.
- **Инъекция в здание `building_railway`:** через `INJECT_OR_CREATE` добавлены новые группы `pmg_gauges_building_railway` и `pmg_automation_building_railway` к ж/д


---
type: concept
description: "Как E&F (снимок 1.13) трогает стройку ваниль: своё частное здание стройки building_ef_private_construction с дешёвыми материалами и выпуском «акций», ликвидность в инфраструктуре, стартовые сектора; ванильный сектор не заменён"
project: vic3
source: ef
aliases: [стройка E&F, private construction E&F]
tags: [ef, механика, стройка]
paths: ["E&F/common/buildings/ef_14_private_construction.txt", "E&F/common/production_methods/14_ef_private_construction.txt", "E&F/common/production_method_groups/14_ef_private_construction.txt", "E&F/common/building_groups/00_ef_building_groups.txt", "E&F/common/buildings/ef_11_private_infrastructure.txt", "E&F/common/defines/00_ef_defines.txt", "E&F/common/history/buildings/00_ef_building.txt"]
verified: "2026-11-12, out E&F без изменений с 1.13 — по файлам; прогоном — нет"
uses: ["[[vanilla/Механики/Стройка]]", "[[vanilla/Потоки/Пул оплачивает частную стройку]]", "[[vanilla/Здания/Строительные сектора]]"]
---
# Стройка (E&F)

## Суть

E&F не заменяет ванильный сектор и не меняет раздачу очков ([[vanilla/Механики/Стройка|механика ваниль]]); он добавляет
**второе здание стройки — частное** `building_ef_private_construction`: те же очки на уровень, что у ваниль (2 / 5 / …),
но материалов в несколько раз меньше и выпуск товара-«акций» `manufacture_stock`, который здание продаёт. Автор E&F
стройку больше не обновляет — снимок 1.13 навсегда.

## Как работает

- **Здание** (`ef_14_private_construction.txt`): группа `bg_ef_private_construction`, `ownership_type = self`,
  `required_construction = construction_cost_medium` (400), технология `urbanization`; государство строить не может
  (`can_build_government = { always = no }`), группы методов — `pmg_base_building_private_construction_sector` и
  `pmg_market_liquidity`.
- **Методы** `pm_*_buildings_private` (`14_ef_private_construction.txt`): деревянные — очки 2, дерево 20, ткань 5,
  выпуск `manufacture_stock` 50, занятость 675 на уровень; чугунные рамы — очки 5, дерево 10, ткань 5, железо 15,
  инструменты 5, «акции» 100; и так далее (против ваниль 75 / 25 дерева и ткани у деревянных).
- **Ликвидность** (`ef_11_private_infrastructure.txt`): `INJECT` `pmg_market_liquidity` в порт, железную дорогу,
  торговый центр; `investment_scores` финансового района с `bg_construction_score`.
- **Defines** (`00_ef_defines.txt`): правки цены национализации и приватизации закомментированы — у E&F они ванильные.

## Потоки — что меняется против ваниль

Частное здание стройки платит за материалы из своей кассы и зарабатывает продажей «акций»; его очки идут в общий запас
страны и делятся по ваниль (казна / пул) — кто платит за очки частного здания, не выяснено.

## Не выяснено

- Платит ли казна или пул движку за очки `building_ef_private_construction`, как за ванильный сектор, и сколько.
- Поведение на ваниль 1.15 — не проверено (мод 1.13).

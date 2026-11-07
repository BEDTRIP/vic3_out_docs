---
type: concept
description: "Закон «Devaluation» — E&F 1.13, `law_devaluation`"
project: vic3
audience: agent
source: ef
aliases: ["Devaluation", "law_devaluation"]
tags: [ef, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_devaluation
paths: [E&F/common/laws/01_ef_monetary_policy.txt]
---
# Devaluation

Закон · `law_devaluation` · `common/laws/01_ef_monetary_policy.txt:36`

## Поля

- **group**: [[ef/Группы законов/Monetary Policy|Monetary Policy]]
- **icon**: `gfx/interface/icons/law_icons/devaluation.dds`
- **disallowing_laws**: [[vanilla/Законы/Изоляционизм|Изоляционизм]], [[ef/Законы/Large Monetary Policy|Large Monetary Policy]]
- **unlocking_technologies**: [[ef/Технологии/Центральный банк (технология)|Центральный банк (технология)]]
- **on_activate**: скрипт, строки 48–50
- **progressiveness**: `50`
- **ai_enact_weight_modifier**: скрипт, строки 54–61

## Ссылаются

- **Законы** (запрещает закон): [[ef/Законы/Large Monetary Policy|Large Monetary Policy]]
- **Идеологии** (lawgroup_monetary_policy: approve): [[ef/Идеологии/Monetary Moderates|Monetary Moderates]], [[ef/Идеологии/Меритократы|Меритократы]], [[ef/Идеологии/Социалисты|Социалисты]]
- **Идеологии** (lawgroup_monetary_policy: neutral): [[ef/Идеологии/Либерализм|Либерализм]]
- **Идеологии** (lawgroup_monetary_policy: strongly_approve): [[ef/Идеологии/Monetary Populists|Monetary Populists]], [[ef/Идеологии/Народничество|Народничество]], [[ef/Идеологии/Пролетарии|Пролетарии]]
- **Идеологии** (lawgroup_monetary_policy: strongly_disapprove): [[ef/Идеологии/Monetary Conservatives|Monetary Conservatives]], [[ef/Идеологии/Monetary Interventionism|Monetary Interventionism]]
- **Методы производства** (открывает закон): [[ef/Методы производства/Devaluation|Devaluation]]

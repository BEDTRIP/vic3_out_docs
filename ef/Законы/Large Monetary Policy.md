---
type: concept
description: "Закон «Large Monetary Policy» — E&F 1.13, `law_large_monetary_policy`"
project: vic3
audience: agent
source: ef
aliases: ["Large Monetary Policy", "law_large_monetary_policy"]
tags: [ef, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_large_monetary_policy
paths: [E&F/common/laws/01_ef_monetary_policy.txt]
---
# Large Monetary Policy

Закон · `law_large_monetary_policy` · `common/laws/01_ef_monetary_policy.txt:64`

## Поля

- **group**: [[ef/Группы законов/Monetary Policy|Monetary Policy]]
- **icon**: `gfx/interface/icons/law_icons/large_monetary_policy.dds`
- **disallowing_laws**: [[vanilla/Законы/Изоляционизм|Изоляционизм]], [[ef/Законы/Revaluation|Revaluation]], [[ef/Законы/Devaluation|Devaluation]]
- **unlocking_technologies**: [[ef/Технологии/Центральный банк (технология)|Центральный банк (технология)]], [[ef/Технологии/Monetary Policy Tools|Monetary Policy Tools]]
- **on_activate**: пусто
- **progressiveness**: `0`
- **ai_enact_weight_modifier**: скрипт, строки 83–85

## Ссылаются

- **Законы** (запрещает закон): [[ef/Законы/Devaluation|Devaluation]], [[ef/Законы/No Monetary Policy|No Monetary Policy]], [[ef/Законы/Revaluation|Revaluation]]
- **Идеологии** (lawgroup_monetary_policy: approve): [[ef/Идеологии/Monetary Interventionism|Monetary Interventionism]]

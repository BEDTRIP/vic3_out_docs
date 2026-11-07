---
type: concept
description: "Закон «No Monetary Policy» — E&F 1.13, `law_no_monetary_policy`"
project: vic3
audience: agent
source: ef
aliases: ["No Monetary Policy", "law_no_monetary_policy"]
tags: [ef, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_no_monetary_policy
paths: [E&F/common/laws/01_ef_monetary_policy.txt]
---
# No Monetary Policy

Закон · `law_no_monetary_policy` · `common/laws/01_ef_monetary_policy.txt:1`

## Поля

- **group**: [[ef/Группы законов/Monetary Policy|Monetary Policy]]
- **icon**: `gfx/interface/icons/law_icons/no_monetary_policy.dds`
- **disallowing_laws**: [[ef/Законы/Large Monetary Policy|Large Monetary Policy]]
- **on_activate**: скрипт, строки 9–11
- **progressiveness**: `50`

## Ссылаются

- **Идеологии** (lawgroup_monetary_policy: approve): [[ef/Идеологии/Monetary Conservatives|Monetary Conservatives]]
- **Идеологии** (lawgroup_monetary_policy: disapprove): [[ef/Идеологии/Народничество|Народничество]], [[ef/Идеологии/Пролетарии|Пролетарии]], [[ef/Идеологии/Социалисты|Социалисты]]
- **Идеологии** (lawgroup_monetary_policy: neutral): [[ef/Идеологии/Monetary Moderates|Monetary Moderates]], [[ef/Идеологии/Monetary Populists|Monetary Populists]], [[ef/Идеологии/Либерализм|Либерализм]], [[ef/Идеологии/Меритократы|Меритократы]]
- **Идеологии** (lawgroup_monetary_policy: strongly_disapprove): [[ef/Идеологии/Monetary Interventionism|Monetary Interventionism]]
- **Методы производства** (открывает закон): [[ef/Методы производства/No monetary policy|No monetary policy]]

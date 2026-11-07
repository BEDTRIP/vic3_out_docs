---
type: concept
description: "Закон «Revaluation» — E&F 1.13, `law_revaluation`"
project: vic3
source: ef
aliases: ["Revaluation", "law_revaluation"]
tags: [ef, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_revaluation
paths: [E&F/common/laws/01_ef_monetary_policy.txt]
---
# Revaluation

Закон · `law_revaluation` · `common/laws/01_ef_monetary_policy.txt:15`

## Поля

- **group**: [[ef/Группы законов/Monetary Policy|Monetary Policy]]
- **icon**: `gfx/interface/icons/law_icons/revaluation.dds`
- **disallowing_laws**: [[vanilla/Законы/Изоляционизм|Изоляционизм]], [[ef/Законы/Large Monetary Policy|Large Monetary Policy]]
- **unlocking_technologies**: [[ef/Технологии/Центральный банк (технология)|Центральный банк (технология)]]
- **on_activate**: скрипт, строки 27–29
- **progressiveness**: `50`
- **ai_will_do**: скрипт, строки 32–34

## Ссылаются

- **Законы** (запрещает закон): [[ef/Законы/Large Monetary Policy|Large Monetary Policy]]
- **Идеологии** (lawgroup_monetary_policy: approve): [[ef/Идеологии/Monetary Moderates|Monetary Moderates]], [[ef/Идеологии/Либерализм|Либерализм]], [[ef/Идеологии/Народничество|Народничество]]
- **Идеологии** (lawgroup_monetary_policy: disapprove): [[ef/Идеологии/Monetary Populists|Monetary Populists]], [[ef/Идеологии/Пролетарии|Пролетарии]]
- **Идеологии** (lawgroup_monetary_policy: strongly_approve): [[ef/Идеологии/Monetary Conservatives|Monetary Conservatives]], [[ef/Идеологии/Меритократы|Меритократы]], [[ef/Идеологии/Социалисты|Социалисты]]
- **Идеологии** (lawgroup_monetary_policy: strongly_disapprove): [[ef/Идеологии/Monetary Interventionism|Monetary Interventionism]]
- **Методы производства** (открывает закон): [[ef/Методы производства/Revaluation|Revaluation]]

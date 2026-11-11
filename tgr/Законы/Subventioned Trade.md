---
type: concept
description: "Закон «Subventioned Trade» — TGR 1.15, `law_ai_subventioned_trade_modern`"
project: vic3
audience: agent
source: tgr
aliases: ["Subventioned Trade", "law_ai_subventioned_trade_modern"]
tags: [TGR, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_ai_subventioned_trade_modern
paths: [TheGreatRevision/common/laws/TGR_TRADE_trade_policy.txt]
---
# Subventioned Trade

Закон · `law_ai_subventioned_trade_modern` · `common/laws/TGR_TRADE_trade_policy.txt:352`

## Поля

- **group**: [[tgr/Группы законов/Торговая политика|Торговая политика]]
- **icon**: `gfx/interface/icons/law_icons/protectionism.dds`
- **progressiveness**: `0`
- **unlocking_technologies**: [[tgr/Технологии/Международная торговля|Международная торговля]]
- **modifier**:
  - [[vanilla/движок/Модификаторы S#^m-state-subvention-export-add|state_subvention_export_add]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-subvention-import-add|state_subvention_import_add]] = `0.25`
  - [[vanilla/движок/Модификаторы S#^m-state-import-advantage-mult|state_import_advantage_mult]] = `0.25`
- **ai_enact_weight_modifier**: скрипт, строки 369–384
- **is_visible**: скрипт, строки 386–388

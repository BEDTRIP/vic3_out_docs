---
type: concept
description: "Закон «Bedel-i Askerî Tax» — VC 1.13, `law_askeri_tax`"
project: vic3
source: vc
aliases: ["Bedel-i Askerî Tax", "law_askeri_tax"]
tags: [VC, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_askeri_tax
paths: [VC/common/laws/joi_taxation.txt]
---
# Bedel-i Askerî Tax

Закон · `law_askeri_tax` · `common/laws/joi_taxation.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Налогообложение|Налогообложение]]
- **parent**: [[vanilla/Законы/Налог на душу населения|Налог на душу населения]]
- **icon**: `gfx/interface/icons/law_icons/per_capita_based_taxation.dds`
- **progressiveness**: `-25`
- **disallowing_laws**: [[vanilla/Законы/Традиционализм|Традиционализм]]
- **unlocking_technologies**: [[vanilla/Технологии/Валютные стандарты|Валютные стандарты]]
- **modifier**:
  - `state_conscription_rate_mult` = `-0.1`
- **tax_modifier_very_low**:
  - `tax_consumption_add` = `0.15`
  - `tax_per_capita_add` = `0.40`
  - `tax_dividends_add` = `0.05`
  - `tax_income_add` = `0.05`
  - `tax_heathen_add` = `0.10`
- **tax_modifier_low**:
  - `tax_consumption_add` = `0.20`
  - `tax_per_capita_add` = `0.55`
  - `tax_dividends_add` = `0.10`
  - `tax_income_add` = `0.10`
  - `tax_heathen_add` = `0.20`
- **tax_modifier_medium**:
  - `tax_consumption_add` = `0.25`
  - `tax_per_capita_add` = `0.70`
  - `tax_dividends_add` = `0.15`
  - `tax_income_add` = `0.15`
  - `tax_heathen_add` = `0.30`
- **tax_modifier_high**:
  - `tax_consumption_add` = `0.30`
  - `tax_per_capita_add` = `0.85`
  - `tax_dividends_add` = `0.20`
  - `tax_income_add` = `0.20`
  - `tax_heathen_add` = `0.40`
- **tax_modifier_very_high**:
  - `tax_consumption_add` = `0.35`
  - `tax_per_capita_add` = `1.0`
  - `tax_dividends_add` = `0.25`
  - `tax_income_add` = `0.25`
  - `tax_heathen_add` = `0.5`
- **is_visible**: скрипт, строки 61–63
- **can_enact**: скрипт, строки 65–70
- **ai_will_do**: скрипт, строки 72–74
- **ai_enact_weight_modifier**: скрипт, строки 76–78

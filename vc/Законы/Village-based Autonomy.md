---
type: concept
description: "Закон «Village-based Autonomy» — VC 1.13, `law_gram_swaraj`"
project: vic3
source: vc
aliases: ["Village-based Autonomy", "law_gram_swaraj"]
tags: [VC, закон]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: law_gram_swaraj
paths: [VC/common/laws/joi_economic_system.txt]
---
# Village-based Autonomy

Закон · `law_gram_swaraj` · `common/laws/joi_economic_system.txt:1`

## Поля

- **group**: [[vanilla/Группы законов/Экономическая система|Экономическая система]]
- **parent**: [[vanilla/Законы/Аграрность|Аграрность]]
- **icon**: `gfx/interface/icons/law_icons/gram_swaraj.dds`
- **progressiveness**: `0`
- **disallowing_laws**: [[vanilla/Законы/Анархия|Анархия]]
- **unlocking_technologies**: [[vanilla/Технологии/Романтизм|Романтизм]]
- **is_visible**: скрипт, строки 17–22
- **can_enact**: скрипт, строки 24–29
- **on_activate**: пусто
- **on_deactivate**: скрипт, строки 34–40
- **modifier**:
  - `state_aristocrats_investment_pool_efficiency_mult` = `0.2`
  - `state_farmers_investment_pool_efficiency_mult` = `0.2`
  - `state_clergymen_investment_pool_efficiency_mult` = `0.2`
  - `building_group_bg_agriculture_throughput_add` = `0.25`
  - `building_group_bg_plantations_throughput_add` = `0.25`
  - `building_group_bg_manufacturing_throughput_add` = `-0.5`
  - `building_group_bg_heavy_industry_construction_efficiency_add` = `-0.25`
  - `building_group_bg_light_industry_construction_efficiency_add` = `-0.25`
  - `building_minimum_wage_mult` = `-0.1`
  - `state_birth_rate_mult` = `0.2`
  - `country_loan_interest_rate_mult` = `-0.5`
  - `country_private_construction_allocation_mult` = `0.5`
  - `building_nationalization_investment_return_add` = `0.5`
  - `country_government_dividends_reinvestment_add` = `0.5`
  - `country_government_dividends_efficiency_add` = `0.25`
  - `country_free_charters_add` = `1`
  - `state_migration_quota_mult` = `1`
  - `country_disable_nationalization_without_compensation_bool` = `yes`
- **ai_will_do**: скрипт, строки 64–69
- **ai_enact_weight_modifier**: скрипт, строки 71–112

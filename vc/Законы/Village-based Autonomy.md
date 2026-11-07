---
type: concept
description: "Закон «Village-based Autonomy» — VC 1.13, `law_gram_swaraj`"
project: vic3
audience: agent
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
  - [[vanilla/движок/Модификаторы S#^m-state-aristocrats-investment-pool-efficiency-mult|state_aristocrats_investment_pool_efficiency_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы S#^m-state-farmers-investment-pool-efficiency-mult|state_farmers_investment_pool_efficiency_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы S#^m-state-clergymen-investment-pool-efficiency-mult|state_clergymen_investment_pool_efficiency_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-agriculture-throughput-add|building_group_bg_agriculture_throughput_add]] = `0.25`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-plantations-throughput-add|building_group_bg_plantations_throughput_add]] = `0.25`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-manufacturing-throughput-add|building_group_bg_manufacturing_throughput_add]] = `-0.5`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-heavy-industry-construction-efficiency-add|building_group_bg_heavy_industry_construction_efficiency_add]] = `-0.25`
  - [[vanilla/движок/Модификаторы B#^m-building-group-bg-light-industry-construction-efficiency-add|building_group_bg_light_industry_construction_efficiency_add]] = `-0.25`
  - [[vanilla/движок/Модификаторы B#^m-building-minimum-wage-mult|building_minimum_wage_mult]] = `-0.1`
  - [[vanilla/движок/Модификаторы S#^m-state-birth-rate-mult|state_birth_rate_mult]] = `0.2`
  - [[vanilla/движок/Модификаторы C#^m-country-loan-interest-rate-mult|country_loan_interest_rate_mult]] = `-0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-private-construction-allocation-mult|country_private_construction_allocation_mult]] = `0.5`
  - [[vanilla/движок/Модификаторы B#^m-building-nationalization-investment-return-add|building_nationalization_investment_return_add]] = `0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-reinvestment-add|country_government_dividends_reinvestment_add]] = `0.5`
  - [[vanilla/движок/Модификаторы C#^m-country-government-dividends-efficiency-add|country_government_dividends_efficiency_add]] = `0.25`
  - [[vanilla/движок/Модификаторы C#^m-country-free-charters-add|country_free_charters_add]] = `1`
  - [[vanilla/движок/Модификаторы S#^m-state-migration-quota-mult|state_migration_quota_mult]] = `1`
  - [[vanilla/движок/Модификаторы C#^m-country-disable-nationalization-without-compensation-bool|country_disable_nationalization_without_compensation_bool]] = `yes`
- **ai_will_do**: скрипт, строки 64–69
- **ai_enact_weight_modifier**: скрипт, строки 71–112

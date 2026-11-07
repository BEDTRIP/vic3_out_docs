---
type: concept
description: "Вид компании «Hitotsubashi (Shueisha, Shogakukan, Kodansha)» — T&R 1.13, `company_hitotsubashi`"
project: vic3
source: tr
aliases: ["Hitotsubashi (Shueisha, Shogakukan, Kodansha)", "company_hitotsubashi"]
tags: [tr, вид-компании]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: company_hitotsubashi
paths: [TechRes+Kuromi/t&r/common/company_types/ztr_comunication_companies.txt]
---
# Hitotsubashi (Shueisha, Shogakukan, Kodansha)

Вид компании · `company_hitotsubashi` · `common/company_types/ztr_comunication_companies.txt:14`

## Поля

- **icon**: `gfx/interface/icons/company_icons/historical_company_icons/japanese_hitotsubashi.dds`
- **background**: `gfx/interface/icons/company_icons/company_backgrounds/comp_illu_publishing.dds`
- **flavored_company**: `yes`
- **preferred_headquarters**: `STATE_KANTO`
- **building_types**: [[tr/Здания/Media Industries|Media Industries]]
- **possible_prestige_goods**: `prestige_good_japanese_anime_manga`
- **potential**: скрипт, строки 27–29
- **attainable**: скрипт, строки 30–36
- **possible**: скрипт, строки 37–47
- **prosperity_modifier**:
  - `building_manzoni_publishing_industry_throughput_add` = `0.15` → [[tr/Здания/Media Industries|Media Industries]]
  - `country_influence_mult` = `0.25`
  - `state_birth_rate_mult` = `-0.02`
- **ai_will_do**: скрипт, строки 53–59
- **ai_construction_targets**: скрипт, строки 60–67
- **ai_weight**: скрипт, строки 68–70

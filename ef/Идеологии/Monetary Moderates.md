---
type: concept
description: "Идеология «Monetary Moderates» — E&F 1.13, `ideology_monetary_moderate`"
project: vic3
source: ef
aliases: ["Monetary Moderates", "ideology_monetary_moderate"]
tags: [ef, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_monetary_moderate
paths: [E&F/common/ideologies/00_ef_ig_ideologies.txt]
---
# Monetary Moderates

Идеология · `ideology_monetary_moderate` · `common/ideologies/00_ef_ig_ideologies.txt:1`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/ideology_monetary_moderate.dds`
- **lawgroup_monetary_system**:
  - [[ef/Законы/Silver Standard|Silver Standard]] = `disapprove`
  - `law_bimetallic_standard` = `approve`
  - `law_gold_exchange` = `approve`
  - [[ef/Законы/Gold Standard|Gold Standard]] = `strongly_approve`
  - [[ef/Законы/No Monetary System|No Monetary System]] = `strongly_disapprove`
  - [[ef/Законы/Fiat Standard|Fiat Standard]] = `strongly_disapprove`
  - [[ef/Законы/External Exchange Standard|External Exchange Standard]] = `strongly_disapprove`
- **lawgroup_bimetalism_ratio**:
  - [[ef/Законы/No Fixed Ratio|No Fixed Ratio]] = `approve`
  - [[ef/Законы/Bimetallic Ratio 201|Bimetallic Ratio 201]] = `disapprove`
  - [[ef/Законы/Bimetallic Ratio 151|Bimetallic Ratio 151]] = `strongly_approve`
  - [[ef/Законы/Bimetallic Ratio 101|Bimetallic Ratio 101]] = `disapprove`
- **lawgroup_monetary_policy**:
  - [[ef/Законы/Revaluation|Revaluation]] = `approve`
  - [[ef/Законы/Devaluation|Devaluation]] = `approve`
  - [[ef/Законы/No Monetary Policy|No Monetary Policy]] = `neutral`

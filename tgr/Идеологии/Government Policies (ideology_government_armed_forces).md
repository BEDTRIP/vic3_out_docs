---
type: concept
description: "Идеология «Government Policies (ideology_government_armed_forces)» — TGR 1.15, `ideology_government_armed_forces`"
project: vic3
audience: agent
source: tgr
aliases: ["Government Policies (ideology_government_armed_forces)", "Government Policies", "ideology_government_armed_forces"]
tags: [TGR, идеология]
generated: "v3 graph objects; ручной раздел — «## Зачем в механике»"
key: ideology_government_armed_forces
paths: [TheGreatRevision/common/ideologies/TGR_POLITICS_ig_ideologies.txt]
---
# Government Policies (ideology_government_armed_forces)

Идеология · `ideology_government_armed_forces` · `common/ideologies/TGR_POLITICS_ig_ideologies.txt:1`

## Поля

- **icon**: `gfx/interface/icons/ideology_icons/modernizer.dds`
- **lawgroup_economic_incentives_secondary**:
  - [[tgr/Законы/No Incentive Focus (economic_incentives_no_focus_secondary)|No Incentive Focus (economic_incentives_no_focus_secondary)]] = `neutral`
  - [[tgr/Законы/Mining Investments|Mining Investments]] = `neutral`
  - [[tgr/Законы/Oil Investments|Oil Investments]] = `approve`
- **lawgroup_economic_incentives_tertiary**:
  - [[tgr/Законы/No Incentive Focus (economic_incentives_no_focus_tertiary)|No Incentive Focus (economic_incentives_no_focus_tertiary)]] = `neutral`
  - [[tgr/Законы/Manufacturing Investments|Manufacturing Investments]] = `neutral`
  - [[tgr/Законы/Light Industry Investments|Light Industry Investments]] = `approve`
  - [[tgr/Законы/Heavy Industry Investments|Heavy Industry Investments]] = `strongly_approve`
- **lawgroup_economic_incentives_public**:
  - [[tgr/Законы/No Incentive Focus (economic_incentives_no_focus_public)|No Incentive Focus (economic_incentives_no_focus_public)]] = `neutral`
  - [[tgr/Законы/Services Investments|Services Investments]] = `neutral`
  - [[tgr/Законы/Public Sector Investments|Public Sector Investments]] = `approve`
  - [[tgr/Законы/Military Sector Investments|Military Sector Investments]] = `strongly_approve`
- **lawgroup_tgr_research_focus**:
  - [[tgr/Законы/No Research Focus|No Research Focus]] = `neutral`
  - [[tgr/Законы/Production Research|Production Research]] = `disapprove`
  - [[tgr/Законы/Military Research|Military Research]] = `strongly_approve`
  - [[tgr/Законы/Society Research|Society Research]] = `disapprove`
- **lawgroup_foreign_policy**:
  - [[tgr/Законы/No Specific Focus|No Specific Focus]] = `neutral`
  - [[tgr/Законы/Diplomatic Embassies|Diplomatic Embassies]] = `disapprove`
  - [[tgr/Законы/Reinforces Foreign perception|Reinforces Foreign perception]] = `approve`
  - [[tgr/Законы/Military Expansionism|Military Expansionism]] = `strongly_approve`
  - [[tgr/Законы/National Sovranism|National Sovranism]] = `approve`
- **lawgroup_centralization**:
  - [[tgr/Законы/Economic Decentralization|Economic Decentralization]] = `strongly_disapprove`
  - [[tgr/Законы/Administrative Decentralization|Administrative Decentralization]] = `disapprove`
  - [[tgr/Законы/Local Autonomies|Local Autonomies]] = `neutral`
  - [[tgr/Законы/Administrative Centralization|Administrative Centralization]] = `approve`
  - [[tgr/Законы/Economic Centralization|Economic Centralization]] = `strongly_approve`
- **lawgroup_tgr_company_participation**:
  - [[tgr/Законы/Private Enterprise 0%|Private Enterprise 0%]] = `disapprove`
  - [[tgr/Законы/Low Nationalization 10%|Low Nationalization 10%]] = `neutral`
  - [[tgr/Законы/Medium Nationalization 25%|Medium Nationalization 25%]] = `approve`
  - [[tgr/Законы/High Nationalization 50%|High Nationalization 50%]] = `strongly_approve`
  - [[tgr/Законы/Public Enterprise 100%|Public Enterprise 100%]] = `approve`

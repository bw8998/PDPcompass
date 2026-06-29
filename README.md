# PDP Compass

## Provider Economics Simulator & Readiness Tool for Filecoin PDP

**PDP Compass** is a public decision-support tool for external machine owners and infrastructure operators who are evaluating whether they can become Filecoin PDP providers.

It is designed to answer one practical question:

> **Can I realistically participate in the Filecoin PDP provider network?**

PDP Compass helps potential providers understand their hardware readiness, monthly cost structure, break-even conditions, workload assumptions, and operational risks before they commit machines, storage, bandwidth, and time.

Our goal is for PDP Compass to become the essential public entry tool for anyone outside the traditional Filecoin SP group who wants to understand and evaluate PDP participation.

---

## Why This Exists

Filecoin PDP and warm storage are becoming important parts of Filecoin’s next service layer. However, many potential providers still lack a clear and realistic way to evaluate whether PDP participation makes sense for them.

Most onboarding efforts focus on explaining what PDP is or how to run a node. But for external machine owners and infrastructure operators, the more important questions are practical and economic:

- Can my existing machines run PDP?
- What hardware or network upgrades are required?
- What will it cost every month?
- What workload assumptions matter?
- What storage price is needed to break even?
- What happens if utilization is low?
- Is this suitable for a former miner, small IDC, Web3 infrastructure operator, NAS / homelab user, or AI server operator?
- What risks should I understand before joining?

PDP Compass focuses on these provider-side decision questions.

It is not a training camp, not a marketing site, and not a revenue promise.

It is a simulator and readiness tool that helps users make better-informed decisions.

---

## Built for External Operators, Not Only Existing Filecoin SPs

PDP Compass is especially designed for external infrastructure operators who are **not already Filecoin Storage Providers**, but may have machines, storage capacity, bandwidth, or operational experience that could support the Filecoin PDP network.

Target users include:

### Former Miners

Machine owners who previously participated in Web3 mining networks and are evaluating new infrastructure opportunities.

### Mining Machine Owners

Individuals or teams that already own machines and want to understand whether PDP is a realistic next use case.

### Web3 Infrastructure Operators

Teams running validators, RPC nodes, indexing infrastructure, compute networks, or other Web3 services.

### Small IDC / Regional Cloud Operators

Infrastructure operators with available storage, bandwidth, and hosting capacity.

### NAS / Homelab Operators

Advanced individual operators who want to understand whether PDP participation is realistic for their setup.

### AI Server / Storage Operators

Operators with machines and storage resources connected to AI workloads.

### Existing Filecoin SPs

Current SPs can also use PDP Compass, but the product is intentionally designed to expand beyond the existing Filecoin SP group.

---

## Core Value

PDP Compass helps potential providers answer:

- **Can I run PDP?**
- **Should I run PDP?**
- **What will it cost?**
- **What workload do I need?**
- **What price do I need to break even?**
- **What risks should I consider?**
- **Am I testnet-ready, pilot-ready, production-ready, or not suitable yet?**

The tool is designed to reduce confusion, unrealistic expectations, and ineffective onboarding.

Instead of asking more people to join PDP blindly, PDP Compass helps identify who is realistically suitable, what conditions are needed, and where the main participation barriers remain.

---

## Why This Is Not Just a Calculator

PDP Compass is not a simple profit calculator.

A basic calculator only asks users to enter costs and revenue assumptions. PDP Compass goes further by combining:

- provider personas
- hardware readiness
- cost modeling
- workload scenarios
- revenue assumptions
- break-even analysis
- readiness scoring
- risk indicators
- field validation from real machine-owner and infrastructure communities

The purpose is not to tell users they will make money.

The purpose is to help them understand whether PDP participation is realistic, what conditions must be true, and what risks they should consider before joining.

This makes PDP Compass valuable not only for individual operators, but also for the Filecoin ecosystem. It can help identify which external operator groups are most likely to become PDP providers, what economic or technical barriers prevent participation, and what kind of support is needed to grow PDP supply beyond existing Filecoin SPs.

---

## Core Features

### 1. Provider Profile Selection

Users choose which type of operator they are:

- Existing Filecoin SP
- Former miner
- Mining machine owner
- Web3 infrastructure operator
- Small IDC / regional cloud provider
- NAS / homelab operator
- AI server / storage operator

Each provider profile may have different assumptions, risks, and readiness levels.

---

### 2. Hardware & Cost Inputs

Users enter key infrastructure parameters:

- CPU / RAM
- SSD / NVMe capacity
- HDD capacity
- existing hardware or new hardware
- electricity cost
- bandwidth cost
- hosting / rack cost
- maintenance cost
- estimated operator time
- hardware depreciation period
- public endpoint availability
- expected uptime

---

### 3. Workload Scenario Builder

Users simulate different PDP participation scenarios:

- storage capacity
- expected utilization
- storage price per TB-month
- retrieval assumptions
- proof / service assumptions
- optional incentive assumptions where applicable
- conservative / base / optimistic cases

---

### 4. Break-even Calculation

The simulator estimates:

- monthly cost
- required break-even price
- monthly revenue scenarios
- net cash flow
- payback period
- cost per TB-month

---

### 5. Readiness Score

PDP Compass gives a practical readiness result:

- Not ready
- Testnet-ready
- Pilot-ready
- Production candidate

The result also explains what is missing, such as:

- public HTTPS endpoint
- storage capacity
- bandwidth stability
- operational monitoring
- cost disadvantage
- unclear workload assumptions

---

### 6. Risk & Sensitivity Indicators

The simulator highlights the variables that most affect the result:

- utilization rate
- storage price
- hardware depreciation
- bandwidth cost
- hosting cost
- uptime requirement
- workload availability
- tooling maturity

The goal is to help users understand uncertainty, not hide it.

---

## Data Credibility and Real-world Validation

PDP Compass will be designed around credible, transparent, and scenario-based data.

We will not rely only on generic assumptions. During development, we will combine:

- official PDP requirements
- objective network and hardware parameters
- real-world hardware asset cost fluctuations
- electricity and bandwidth cost assumptions
- hosting / rack / maintenance cost ranges
- user-provided infrastructure data
- feedback from machine owners and mining communities
- external testing results
- input from Filecoin ecosystem teams where possible

We plan to seek data support and feedback from:

- Filecoin Foundation
- SPWG
- Filecoin Onchain Cloud
- PDP ecosystem contributors
- machine owners
- former miners
- Web3 infrastructure operators
- mining and infrastructure communities

The goal is not to create a perfect prediction engine. The goal is to create a realistic and transparent decision tool that external operators can trust enough to use.

---

## Methodology

PDP Compass uses a transparent scenario-based model.

Inputs are categorized by source type:

| Source Type | Meaning |
|---|---|
| Official | Filecoin / PDP / ecosystem documentation |
| Market | Hardware, electricity, bandwidth, and hosting market assumptions |
| Observed | Feedback or samples from infrastructure operators |
| User-provided | Inputs entered by the simulator user |
| Assumed | Scenario-based assumptions used for conservative / base / optimistic cases |

PDP Compass does not guarantee revenue.

It helps users understand cost structure, readiness gaps, break-even conditions, and major risk variables.

---

## Example Output

A simulator result may include:

```text
Provider Type: Former Miner
Available Storage: 50 TB
Readiness: Pilot-ready

Monthly Cost: $430
Break-even Price: $14.30 / TB-month

Conservative Scenario: -$180 / month
Base Scenario: +$75 / month
Optimistic Scenario: +$310 / month

Key Risk: utilization rate
Missing Requirement: stable public endpoint

Recommendation:
Start with a 10 TB pilot workload before committing more capacity.
```

---

## UI Philosophy

PDP Compass should not feel like an internal spreadsheet or a research model.

We care deeply about usability.

The product will be designed with a clean, accessible, and mainstream-friendly UI so that more external operators can understand the results, trust the logic, and come back to use the tool as PDP evolves.

The UI should make PDP participation easier to evaluate for people who may not be deeply embedded in the Filecoin ecosystem yet.

Design goals:

- simple language
- clear step-by-step input flow
- readable results
- scenario comparison
- strong visual distinction between assumptions and observed data
- exportable result summary
- mobile-friendly access where practical

A good simulator is not only mathematically useful. It must also be easy enough for real operators to use repeatedly.

---

## Documentation and Community Reference

All survey frameworks, parameter categories, model assumptions, testing feedback, and methodology updates generated during the project will be documented.

Where sensitive operator data is involved, it will be anonymized.

The goal is to create not only a simulator, but also a reusable knowledge base for the Filecoin community to understand:

- PDP provider economics
- external operator readiness
- hardware and cost barriers
- workload assumptions
- onboarding friction
- why some operators are suitable and others are not

PDP Compass should help the ecosystem learn from real provider-side feedback instead of repeating the same onboarding assumptions.

---

## Project Scope

This project will be completed in two milestones.

### Milestone 1: Model Architecture, Sample Data Collection & UI Prototype

Focus:

- provider persona framework
- cost model
- revenue scenario model
- readiness scoring framework
- sample input collection
- UI prototype
- methodology draft

### Milestone 2: Simulator MVP, External Testing & Public Launch

Focus:

- public web simulator
- provider profile selection
- cost / workload / revenue inputs
- break-even output
- readiness result
- risk indicators
- 20+ external test submissions
- final public launch

---

## What This Project Is Not

PDP Compass is not:

- a PDP node implementation
- a PDP training camp
- a provider marketplace
- a guaranteed revenue calculator
- financial advice
- a mining return promise
- a replacement for official PDP documentation
- a tool that assumes everyone should become a PDP provider

It is a provider decision-support tool.

---

## Why Our Team

PDP Compass will be led by Bella and a small team with experience in Filecoin network and mining hardware services, Web3 mining projects, and miner community operations.

We were SP and have participated in multiple Web3 mining and compute-related networks, including Aleo, io.net, and other mining projects. Through this work, we have built access to communities of machine owners, individual miners, and Web3 infrastructure participants.

This is directly relevant to PDP Compass because potential PDP providers will ask the same questions miners usually ask before joining a new network:

- What hardware do I need?
- What are the monthly costs?
- What is the break-even point?
- What workload or revenue assumption makes participation worthwhile?
- What are the operational risks?

We understand the provider-side audience because we work directly with miners, machine owners, and Web3 infrastructure participants.

PDP Compass is built for them.

---

## Disclaimer

PDP Compass is a decision-support simulator.

It does not guarantee PDP provider revenue and should not be treated as financial advice.

All results are based on user-provided inputs, public documentation, market assumptions, observed samples, and scenario modeling. Actual provider economics may vary depending on workload availability, storage pricing, retrieval demand, uptime requirements, hardware cost, bandwidth cost, and future Filecoin ecosystem conditions.

---

## Status

This project is in pre-submission / early design stage.

The simulator has not yet been fully built.

The grant-funded work will turn the current framework into a polished public simulator, collect provider-side sample data, validate the model with external testers, and launch the tool for the Filecoin PDP ecosystem.
```

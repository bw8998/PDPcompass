# Simulator Methodology

PDP Compass uses scenario-based modeling.

The simulator does not predict guaranteed income. It estimates cost structure, break-even conditions, and readiness based on user inputs and transparent assumptions.

## Monthly Cost

Monthly Cost =

- hardware amortization
- electricity cost
- bandwidth cost
- hosting / rack cost
- maintenance cost
- operator labor cost
- endpoint / domain / monitoring cost
- risk buffer

## Monthly Revenue

Monthly Revenue =

- storage revenue
- retrieval revenue if applicable
- proof / service revenue if applicable
- optional incentive assumptions if applicable

## Break-even Price

Break-even price per TB-month = Monthly Cost / Usable Paid TB

Usable Paid TB = Raw Capacity × Utilization Rate × Availability Factor

## Scenario Outputs

The simulator should show:

- conservative case
- base case
- optimistic case

## Source Types

Every parameter should be labeled as:

- Official
- Market
- Observed
- User-provided
- Assumed

## Limitations

The simulator cannot guarantee actual revenue.

Actual provider economics depend on workload availability, customer demand, Filecoin ecosystem conditions, PDP tooling maturity, pricing, and provider reliability.

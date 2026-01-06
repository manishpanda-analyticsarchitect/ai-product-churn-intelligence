# Churn Risk Scoring

Instead of binary predictions, churn probability is converted into actionable
risk bands.

## Risk Bands
- Low Risk: Probability < 30%
- Medium Risk: 30% – 60%
- High Risk: > 60%

## Usage
Risk bands allow non-technical stakeholders to prioritize intervention without
interpreting raw ML outputs.

## Alerting Thresholds

To avoid alert fatigue, churn probabilities are mapped to alert levels:

- >80% → Hard Alert (Immediate CS intervention)
- 60%–80% → Soft Alert (Proactive outreach)
- 30%–60% → Monitor
- < 30% → No Action

This ensures alerts are both actionable and trusted by stakeholders.

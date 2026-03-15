# 02 – Risk Scoring Engine

This module introduces a simple but powerful risk scoring model tailored to healthcare environments, with a specific focus on human-factor risk.

## Risk Scoring Formula

Risk Score = Likelihood × Impact × Human-Factor Modifier

- **Likelihood (L):** Probability of the threat occurring.
- **Impact (I):** Severity of operational, clinical, or PHI consequences.
- **Human-Factor Modifier (H):** Adjusts risk based on behaviour, fatigue, training, and workflow pressure.

## Scoring Scales

### Likelihood (1–5)
1 – Rare  
2 – Unlikely  
3 – Possible  
4 – Likely  
5 – Almost Certain  

### Impact (1–5)
1 – Minimal impact, no PHI exposure  
2 – Low impact, minor disruption  
3 – Moderate impact, limited PHI exposure  
4 – High impact, major disruption  
5 – Critical impact, significant PHI exposure or patient safety risk  

### Human-Factor Modifier (0.8–1.5)
0.8 – Strong culture, low fatigue  
1.0 – Normal conditions  
1.5 – High pressure, workarounds, poor training  

## Sample Risk Register

| Scenario                                | L | I | H   | Risk Score |
|----------------------------------------|---|---|-----|-----------|
| Phishing email to clinic staff         | 4 | 3 | 1.4 | 16.8      |
| Lost unencrypted mobile device         | 3 | 4 | 1.2 | 14.4      |
| Misconfigured S3 bucket with PHI       | 2 | 5 | 1.1 | 11.0      |
| Shadow IT AI tool used for PHI         | 3 | 5 | 1.5 | 22.5      |

## Objective

Enable healthcare leaders to prioritize cyber risks based not only on technical exposure, but also on operational pressure and human behaviour.

# Fitness Studio Member Churn Prediction

*Updated February 2026*

---

## The members you're about to lose are already showing you the signs

Churn rarely happens overnight. Members don't cancel out of nowhere. They stop showing up consistently, then occasionally, then not at all. By the time they cancel, the decision was made weeks earlier.

This project builds an early warning system for exactly that pattern. Using behavioral and demographic data from 2,081 fitness studio members across 9 locations, it identifies which members are at risk of churning before they leave, and translates those signals into a retention playbook that studio leadership can act on immediately.

The approach is not specific to fitness studios. Any subscription-based business where member engagement can be measured — fitness, healthcare, fintech, SaaS — faces the same fundamental challenge: finding the at-risk customer before they walk out the door.

---

## Key Results

| Metric | Value |
|---|---|
| Members in dataset | 2,081 across 9 studio locations |
| Overall churn rate | 34.9% |
| Model accuracy | 68% |
| Precision on churn flags | 58% |
| Primary churn drivers | Engagement score and membership tenure |
| Auto-renew impact | Negligible — not a meaningful retention lever |

### Churn Rate by Studio Location

| Studio | Churn Rate |
|---|---|
| Highlands Ranch | 38.4% — highest |
| Hilltop Village | 37.9% |
| Castle Rock | 36.7% |
| Uptown Denver | mid-30s |
| Applewood Village | mid-30s |
| Lowry | 29.2% — lowest |

### Active vs Churned Member Comparison

| Metric | Active Members | Churned Members |
|---|---|---|
| Average engagement score | 63.2 | 52.4 |
| Average tenure (months) | 36.9 | 26.8 |
| Avg weekly classes (last 6 months) | 2.5 | 2.0 |
| Monthly membership cost | $184.30 | $184.60 |

Price is not the driver. Behavior is.

---

## Model Comparison

| Metric | Logistic Regression | Random Forest |
|---|---|---|
| Accuracy | 67.8% | 61.0% |
| Precision (churn flags) | 57.7% | 42.6% |
| Recall (churners caught) | 29.4% | 34.4% |
| AUC | 0.650 | 0.610 |

Logistic Regression was selected as the operational model. Higher precision means fewer wasted interventions — when it flags a member as at risk, it is right more than half the time.

---

## The Recommendation

**High risk — personal, direct, immediate**
Direct outreach from studio staff. A phone call, in-person conversation, or personal message from a coach before the decision to cancel is made.

**Medium risk — targeted digital communication**
Personalized emails with class suggestions, milestone recognition, or challenges to rebuild engagement without requiring staff time for every interaction.

**Low risk — general loyalty programming**
Community initiatives, recognition programs, and consistent value delivery. Do not over-invest here at the expense of the higher-risk tiers.

### Win the First Six Months

Churn risk drops sharply after the six-month mark. Members who build consistent attendance habits in the first six months are far more likely to stay long term. The highest-return retention investment is not winning back members who have already decided to leave — it is preventing the decision from being made in the first place.

---

## Repository Structure
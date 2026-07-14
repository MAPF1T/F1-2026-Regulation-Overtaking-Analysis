# F1-2026-Regulation-Overtaking-Analysis
Statistical analysis of whether Formula 1's 2026 regulation changes (active aero, overtake mode) increased overtaking frequency, comparing matched circuits from the 2025 and 2026 seasons.

Hello, I am a high school student interested in pursuing a major in statistics, with an deep interest and passion in watching Formula 1. Following the 2026 season, F1 introduced its most significant regulation overhaul in years, such as new hybrid power units with a 50:50 power split, active aerodynamics, and a new "Overtake Mode" systemall explicitly intended to make overtaking easier and racing closer. I saw this as an opportunity to apply statistical methods I've learned in school (AP Statiscs) and through independent study to test whether these regulation changes actually achieved their stated goal, using real race data from the 2025 and 2026 seasons.

## Background
Formula 1's grid position (qualifying result) has traditionally been considered a strong predictor of final race position, particularly at circuits where overtaking is difficult. Starting in 2026, several rule changes were introduced specifically to reduce this predictability and increase overtakes:

| Change | Description |
|---|---|
| Active Aero | Front/rear wings adjust automatically between corners and straights, replacing the previous fixed-wing + DRS system |
| Overtake Mode | Attacking cars within 1 second of the car ahead gain temporary extra deployable electrical power |
| Power Unit Overhaul | Shift to a 50:50 combustion/electric power split, changing how drivers manage energy through a lap |

To evaluate whether these changes had a measurable effect, this project compares overtaking frequency between the 2025 season (before regulation changes) and the 2026 season (after regulation changes) at circuits that appear in both seasons' calendars, using data retrieved via --

## Research Question

**"Did F1's 2026 regulation changes increase overtaking frequency compared to the 2025 season?"**

## Sub Question 1
"At circuits common to both the 2025 and 2026 seasons, how does the average overtaking index (mean absolute change between grid and finishing position) compare between the two seasons?"

**Methods used:** Data Cleaning (DNF Filtering), Descriptive Statistics, Paired Comparison by Circuit

## Sub Question 2
"Is the difference in overtaking index between the 2025 and 2026 seasons statistically significant?"

**Method used:** Paired Sample t-Test

---

**Limitations**: Because there were multiple simultaneous regulation changes (power unit, aerodynamics, tires, fuel), any observed difference in overtaking index can be attributed to the 2026 regulation package as a whole, not to any single rule change in isolation.
